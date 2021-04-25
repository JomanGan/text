<br>
<div align="center">
📘 Summary
</div> 
<br>

> “学了却没有改变生活，那其实就是根本没学会。” ​​​ ——《新生：七年就是一辈子》  

<b><details><summary>💡 提示</summary></b>

> 📘 Summary 的页面无法使用目录跳转

</details>


<b><details><summary>💻 操作系统</summary></b>
  
##### TCP 三次握手建立连接

【TCP 建立连接全过程解释】

1. 客户端发送 SYN 给服务器，说明客户端请求建立连接；
2. 服务端收到客户端发的 SYN，并回复 SYN+ACK 给客户端（同意建立连接）；
3. 客户端收到服务端的 SYN+ACK 后，回复 ACK 给服务端（表示客户端收到了服务端发的同意报文）；
4. 服务端收到客户端的 ACK，连接已建立，可以数据传输。

##### TCP 为什么要进行三次握手？

【答案一】因为信道不可靠，而 TCP 想在不可靠信道上建立可靠地传输，那么三次通信是理论上的最小值。（而 UDP 则不需建立可靠传输，因此 UDP 不需要三次握手。）

> [Google Groups . TCP 建立连接为什么是三次握手？{技术}{网络通信}](https://groups.google.com/forum/#!msg/pongba/kF6O7-MFxM0/5S7zIJ4yqKUJ)

</details>


<b><details><summary>📜 License</summary></b>
  转载请注明出处</details>
