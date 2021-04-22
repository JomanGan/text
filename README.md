<br>
<div align="center">
📘 Summary
</div> 
<br>

<b><details><summary>💡 提示</summary></b>

右侧目录支持方式：

* 语雀的镜像仓库：[C/C++ 面试基础知识总结](https://www.yuque.com/huihut/interview/readme)
* Github + TOC：[jawil/GayHub TOC 导航](https://github.com/jawil/GayHub)

> 📘 Summary 的 README 页面无法使用目录跳转，请在 [📖 Details](https://github.com/huihut/interview/blob/master/README_Details.md) 页面使用

</details>

<b><details><summary>➕ C/C++</summary></b>




---
### C 实现 C++ 类

> [C 语言实现封装、继承和多态](http://dongxicheng.org/cpp/ooc/)    


<details><summary>explicit 使用</summary> 


### Google C++ Style Guide

> 英文：[Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)  
> 中文：[C++ 风格指南](https://zh-google-styleguide.readthedocs.io/en/latest/google-cpp-styleguide/contents/)
<details><summary>Google C++ Style Guide 图</summary>

![Google C++ Style Guide](images/GoogleCppStyleGuide.png)

> 图片来源于：[CSDN . 一张图总结Google C++编程规范(Google C++ Style Guide)](https://blog.csdn.net/voidccc/article/details/37599203)

</details>

### 牛客网

* [牛客网 . 在线编程专题](https://www.nowcoder.com/activity/oj)

</details>

<b><details><summary>💻 操作系统</summary></b>
  
##### TCP 三次握手建立连接

![UDP 报文](images/TCP三次握手建立连接.png)

【TCP 建立连接全过程解释】

1. 客户端发送 SYN 给服务器，说明客户端请求建立连接；
2. 服务端收到客户端发的 SYN，并回复 SYN+ACK 给客户端（同意建立连接）；
3. 客户端收到服务端的 SYN+ACK 后，回复 ACK 给服务端（表示客户端收到了服务端发的同意报文）；
4. 服务端收到客户端的 ACK，连接已建立，可以数据传输。

##### TCP 为什么要进行三次握手？

【答案一】因为信道不可靠，而 TCP 想在不可靠信道上建立可靠地传输，那么三次通信是理论上的最小值。（而 UDP 则不需建立可靠传输，因此 UDP 不需要三次握手。）

> [Google Groups . TCP 建立连接为什么是三次握手？{技术}{网络通信}](https://groups.google.com/forum/#!msg/pongba/kF6O7-MFxM0/5S7zIJ4yqKUJ)

【答案二】因为双方都需要确认对方收到了自己发送的序列号，确认过程最少要进行三次通信。

> [知乎 . TCP 为什么是三次握手，而不是两次或四次？](https://www.zhihu.com/question/24853633/answer/115173386)

【答案三】为了防止已失效的连接请求报文段突然又传送到了服务端，因而产生错误。

> [《计算机网络（第 7 版）-谢希仁》](https://github.com/huihut/interview/blob/master/images/TCP-transport-connection-management.png)
> 


<b><details><summary>📜 License</summary></b>
