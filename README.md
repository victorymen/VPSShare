# **VPSShare技术及应用白皮书**
## **一、摘要**
近几年随着区块链的快速发展，各国政府也开始高度重视区块链的发展，随着国内对数字货币的进一步管制，各个交易平台开始走向海外市场，从最近的管制中我们可以看的到，政府接下来将进一步封锁网站，导致部分用户无法访问，比如币安。如果用户想继续访问，只能通过购买市面上常见的vpn。vpn市场鱼龙混杂，经常性的被封锁，团队无法联系，用户的钱财遭到损失，而团队又重新搞一个，旧戏重演。收费也是一个很大的问题，如果用户按照正常的手续来购买代理服务，团队和用户的信息都将是不安全的、可追踪的。区块链的到来很完美的解决了这些问题。我们可以利用区块链的匿名性和去中心化技术，为用户提供一个去中心化的代理使用平台。
## **二、VPSSHARE基础介绍**
 1、什么是VPS
虚拟专用服务器，是指通过虚拟化技术在独立服务器中运行的专用服务器。每个使用VPS技术的虚拟独立服务器拥有各自独立的公网IP地址、操作系统、硬盘空间、内存空间、CPU资源等，还可以进行安装程序、重启服务器等操作，与运行一台独立服务器完全相同。
2、什么是VPN
vpn在很多人心目中就是用来翻墙的工具，其实不是。vpn最主要的功能，并不是用来翻墙，只是它可以达到翻墙的目的。vpn--虚拟专用网络，它的功能是：在公用网络上建立专用网络，进行加密通讯。在企业网络和高校的网络中应用很广泛。你接入vpn，其实就是接入了一个专有网络，你的网络访问都从这个出口出去，你和vpn之间的通信是否加密，取决于你连接vpn的方式或者协议。
3、VPS怎么用
ss是github上的一个开源项目，通过socks5代理，。socks代理只是简单的传递数据包，而不必关心是何种协议，所以socks代理比其他应用层代理要快的多。socks5代理是把你的网络数据请求通过一条连接你和代理服务器之间的通道，由服务器转发到目的地，这个过程中你是没有通过一条专用通道的，只是数据包的发出，然后被代理服务器收到，整个过程并没有额外的处理。通俗的说，现在你有一个代理服务器在香港，比如你现在想要访问google，你的电脑发出请求，流量通过socks5连接发到你在香港的服务器上，然后再由你在香港的服务器去访问google，再把访问结果传回你的电脑，这样就实现了翻墙。而VPS就是这个中介服务器。
4、VPN和VPS代理的区别
ss抗干扰性强，而且对流量做了混淆，所有流量在通过防火墙的时候，基本上都被识别为普通流量，也就是说你翻墙了，但是政府是检测不到你在翻墙的。两者的出发点和着重点就不同，ss更注重流量的混淆加密。速度方面ss是远远优胜于VPN。而安全性方面国内vpn服务商，政府是很容易拿到他们的服务器日志的，如果他们真的这样做了，你翻墙做了什么，一览无余。
因为vpn是走的专用通道，它是用来给企业传输加密数据用的，所以vpn的流量特征很明显，以openvpn，蓝灯为例，流量特征明显，防火墙直接分析你的流量，如果特征匹配，直接封掉。目前就翻墙来说，PPTP类型的vpn基本死的差不多了，L2TP大部分地区干扰严重很不稳定。
## **三、通过VPS共享+区块链我们可以干什么**
矿工通过共享自己的云服务器链接到VPSShare区块网络，用户通过移动终端连接到区块网络，区块网络通过最佳连接算法，把闲置的网络资源分配给用户。这一切的服务都基于VPScoin，用户在使用代理的时候通过燃烧代币来获得服务，价格远远低于VPN的价格。代币可以随时通过app用以太坊或者其他数字资产进行兑换。App同时充当钱包和代理上网的角色。矿工通过共享云服务器，可以获得一定的代币作为收益。
去中心化的代理服务，是个人和矿工之间利益的往来，没有第三方的干涉，团队没有为用户提供任何的代理服务，也不存储用户的任何信息。
## **四、VPSSHARE原生资产**
1、	VPSCoin价值基础
VPSCoin是VPSShare的原生资产，通过燃烧VPSCoin用户获得网络代理服务，一部分代币通过燃烧奖励给提供服务的矿工，一部分作为代理使用的手续费，奖励给开发者，一部分销毁掉，当销毁达到一定数量停止。
