# packetBuilder
这是一个数据包生成器。

是我几年前为了验证之前学的TCP/IP原理，CCNP(思科高级网络工程师)相关底层知识而写的一个C语言开发的工具。

缺点是代码比较原始，没有抽象封装出来，方便别人调用，但绝对是学习互联网底层的好东西。

优点是:

1、带有大量中文注释。

2、基于原始套接字构造各种常见的和不常见的数据包，包括TCP, UDP, HTTP, DNS, ARP等数据包。

3、支持任意报头字段设置。

4、支持负载内容自定义。
