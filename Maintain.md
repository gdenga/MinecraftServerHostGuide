# 第七节 系统运行维护
我们都知道，与普通家用电脑不同的是，服务器是一台24小时不关机的电脑。正因如此，我们就不能把使用家用电脑的习惯带到使用服务器上去。

## 杀毒软件
一般情况下，服务器只会运行一项业务，例如搭建我的世界服务器时，不推荐再搭建其他游戏。

这是因为，每种程序对服务器的配置和环境要求是不同的。我们购买到的VPS服务器虽然可以搭建其他游戏，但是服务商不会在硬件上对其他游戏进行优化，服务商的售后也无法提供其他游戏的支持。 

所以，在服务器上**切勿**安装**非**搭建我的世界服务器必要的软件，**尤其不能**安装360安全卫士和腾讯电脑管家之类的家用电脑常见的安全软件。这类安全软件会更改系统设置，可能会影响到我的世界服务器的运行，甚至有可能使服务器无法连接网络。

我们也同样**不建议**安装杀毒软件的所谓服务器版或安全狗等服务器防黑安全软件，通常情况下，这类软件无法提供实质性的防御效果，反而可能会影响我的世界服务器的正常运行，同时也可能使服务器无法连接网络。

## 运行环境
搭建我的世界服务器需要的一些环境（如Java），可能会在第一次安装过后有所更新，但我们并**不建议**你时常对这些环境进行更新，尽管环境的开发团队会尽可能对新版本进行兼容性测试，但我们谁也无法保证新版本不存在任何兼容性问题。

**如果你的服务器没有出现任何问题，就请不要再做任何操作，那样只会是画蛇添足！**

## 内存维护
在系统和我的世界服务器的运行中，会不间断产生一些内存数据垃圾，这些数据垃圾无法被软件回收。长此以往，VPS服务器的内存将会充斥这些垃圾，而系统和我的世界服务器将无法正常运行。尽管这个过程可能会持续很长时间，但仍然是个不容小觑的问题，我们**建议**你在我的世界服务器没有玩家时，对VPS服务器进行重启，以此彻底清理内存垃圾，释放内存空间，保障系统和我的世界服务器的正常运行。

## 系统安全
数据无价，系统安全是重中之重。一般情况下，除阿里云等大型企业公有云外，我们购买的用于搭建我的世界服务器的VPS服务器，它的默认系统密码是固定的（如`Example!.`），你得到的服务器系统密码与他人的服务器系统密码是同一个。

同时，大多数我的世界服务器提供商为VPS服务器对外开放的端口是有规律的。因此，不法者便可以通过这种规律，从一台VPS服务器的后台信息推断出其他VPS服务器的后台信息，如果你没有修改默认的系统密码，那么不法者便可以直接进入你的VPS服务器后台，获取到完全控制权限，你的数据便落入他人手中。

所以，**在拿到VPS服务器后台信息时，第一时间修改系统密码！**
