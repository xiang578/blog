---
title: 计算机基础：计算机网络
date: 2017-04-29 21:57:37
tags: [network,computer]
categories: 程序园
---

1. 电路交换与分组交换的区别？ 优劣对比。
 
2. OSI有哪几层，知道主要几层的各自作用。
    1. 物理层：定义通信与传输借口硬件的机械、电气、功能和过程特性，实现比特流的透明传输。
    2. 数据链路层：无差别传送以帧为单位的数据。
    3. 网络层：选择合适的路由和交换结点，分组或者包。
    4. 运输层：端到端、或者进程到进程的无差别传送。
    5. 会话层：对数据传输的同步进行管理
    6. 表示层：信息加密和解密，正文压缩和还原
    7. 应用层：
 
3. TCP/IP有哪几层，会画出来，知道所有层数的作用，会列举各层主要的协议名称。
    1. 网络接口层：x.25
    2. 网际层：IP
    3. 运输层：TCP和UDP
    4. 应用层：HTTP、FTP等
 
4. 硬件(MAC)地址的概念及作用。
    1. 媒体访问控制子层：前6位16进制IETF分配。
    2. 区分不同的硬件
 
5. ARP协议的用途 及算法、在哪一层上会使用 ARP ？
    1. 地址解析协议：IP地址到MAC地址的映射
    2. 网络层
    3.  
 
8. 知道各个层使用的是哪个数据交换设备。（交换机、路由器、网关）
 
    1. 物理层：中继器、集线器
    2. 数据链路层：网桥或者交换机
    3. 网络层中继系统：路由器
    4. 网络层以上：网关
 
11. IP报文的格式，格式的各个字段的含义要理解。
 
12. MTU的概念，啥叫路径MTU？ MTU发现机制，TraceRoute(了解)。
 
13. RIP协议的概念 及算法。
 
14. ICMP协议的主要功能。
 
    1. 网际控制报文协议，提高IP数据报成功交付的机会，报告差错和异常情况。
 
15. 组播和多播的概念，IGMP的用途。
 
16. Ping协议的实现原理，ping 命令格式。
 
    1. 应用层，使用网络层的ICMP协议
 
17. 子网划分的概念，子网掩码。
 
    1. A类子网掩码：255.0.0.0，划分：8位+子网X位+主机24-X位
 
18. IP地址的分类，如何划分的，及会计算各类地址支持的主机数。
 
19. DNS的概念，用途，DNS查询的实现算法。
 
20. TCP与UDP的概念，相互的区别及优劣。
    - TCP和UDP是OSI模型中的运输层中的协议。TCP提供可靠的通信传输，而UDP则常被用于让广播和细节控制交给应用的通信传输。
    - TCP面向连接，UDP面向非连接即发送数据前不需要建立链接
    - TCP提供可靠的服务（数据传输），UDP无法保证
    - TCP面向字节流，UDP面向报文
    - TCP数据传输慢，UDP数据传输快
    
21. UDP报文的格式，字段的意义。
 
22. TCP 报文的格式，字段的意义。
 
23. TCP通过哪些措施，保证传输可靠？
 
24. 三次握手，四次断开过程。
 
    1. 客户端向服务器发送一个SYN j
    2. 服务器向客户端响应一个SYN k，并对SYN j进行确认 ACK j+1
    3. 客户端向服务器发送一个ACK k+1
    4. 一端发送一个FIN
    5. 另一端接收到这个FIN分节后，执行被动关闭，对这个FIN进行确认，继续传输数据。
    6. 发送数据之后，发送一个FIN
    7. 接受到FIN，结束传输。
 
25. TIME_WAIT状态的概念及意义。
 
26. 滑动窗口协议 与 停止等待协议的区别。
 
27. TCP的流量控制和拥塞控制实现原理(会画拥塞控制的典型图)。
 
28. TCP的快速重传与快速恢复算法。
 
29. TFTP 与 FTP的区别。
 
30. 阻塞方式和非阻塞方式，阻塞connect与非阻塞connect。(比较难，有兴趣可以了解)
 
31. HTTP基本格式。（java程序员必须掌握）
 
 


