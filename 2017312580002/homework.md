#网絡及分布式作業1
#周梓浩-2017312580002

Ping命令:

![ping](https://raw.githubusercontent.com/worprime/DNAP-HOMEWORK-1/master/2017312580002/photo1.png)
ping主要用來查看网絡的情況,通過發送數据包到目标地址的主机之后主机返回应答包。可以看到这一次ping命令一共發送了四个數据包到目标主机,并没有發生掉包的情況。而TTL都是57,代表指定数据报被路由器丢弃之前允许通过的网段数量,所以應該經過了64-57=7个路由器。

tracert命令:

![tracert](https://raw.githubusercontent.com/worprime/DNAP-HOMEWORK-1/master/2017312580002/photo2.png)

tracert命令可以得到主机到目标主机经过路由器的ip。通過ping命令的ttl,可以計算出个經過了几个路由器,tracert命令就可以直接得到經過的路由器ip地址和數量。
