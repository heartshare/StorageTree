# StorageTree
存储系统

<pre>
存储的分类
      1）封闭系统的存储
      2）外挂存储
         1）DAS
         2) NAS
         3) SAN
</pre>

<pre>
DAS
      直接附加存储，是指将存储设备通过SCSI接口或者光纤通道直接连接到一台服务器上。
      当服务器在地理位置上比较分散，很难通过远程进行互联时，采用DAS是比较好的解决方案
</pre>

<pre>
NAS   
      网络附加存储，是指通过网络交换机连接存储系统和服务器，建立专门用于数据存储的私有网络
      用户通过TCP/IP协议访问数据，采用业界标准的文件共享协议，如NFS/HTTP/CIFS来实现基于
      文件级的共享。
      NAS存储是文件共享访问变得更方便和快捷，在一定程度上限制了NAS的网络传输能力
</pre>

<pre>
SAN
      SAN是存储区域网络的简称，是指一种通过光纤交换机，光纤路由器，光纤集线器等设备将磁盘
      阵列，磁带等存储设备与相关的服务器连接起来的高速专用子网。
      SAN由三部分组成：
           1：连接设备， 如光纤路由器，光纤交换机，光纤集线器，
           2：接口如SCSI, FC, 
           3：通信协议如 IP, SCSI
      这三部分再加上存储设备和服务器构成了一个SAN系统。

      SAN提供了灵活，高性能，高扩展性的存储网络环境，它可以更加有效的传输海量的数据块。
      由于采用光纤接口，因此SAN还具有更高的带宽，同时SAN也使统一管理和集中控制简化。
</pre>
