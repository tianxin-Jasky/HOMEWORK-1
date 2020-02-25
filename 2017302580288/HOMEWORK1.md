# 第一次作业

李沛昊  2017302580288



## 1、ping一台电脑

​	PING （Packet Internet Groper），因特网包探索器，用于测试网络连接量的程序 [1]  。Ping是工作在 TCP/IP网络体系结构中应用层的一个服务命令， 主要是向特定的目的主机发送 ICMP（Internet Control Message Protocol 因特网报文控制协议）Echo 请求报文，测试目的站是否可达及了解其有关状态。

​	在命令行中使用ping指令：ping 192.168.1.4， 结果如下：

![ping指令](./Asset\TIM截图20200224124022.png)

## 2、tracert一个服务器

​	tracert（跟踪路由）是路由跟踪实用程序，用于确定 IP 数据包访问目标所采取的路径。tracert 命令用 IP 生存时间 (TTL) 字段和 ICMP 错误消息来确定从一个主机到网络上其他主机的路由。

​	我使用tracert命令跟踪本机到baidu服务器的路由路径：tracert www.baidu.com，结果如下:

![tracert百度服务器](./Asset\TIM截图20200224141209.png)

## 3、申请github账户，下载wireshark

​	我已拥有GitHub账户，账户：https://github.com/JeffLeeZero

​	考虑到家里网速不足，直接从github上clone项目速度很慢，我先用github账户fork了wireshark的项目仓库，再将该仓库迁移到码云上，并用git从码云上将该项目clone到本地：

![项目迁移到码云](./Asset\TIM截图20200224165212.png)

![clone到本地](./Asset\TIM截图20200224165246.png)