```
原创内容，转载请注明出处, 谢谢~
```

## 环境要求

* php 7.2.1
* swoole 2.0.13


## 交流&吐槽

> qq群

**入群时请备注`swoole内核剖析`，(^_^)谢谢~**

`群号：610038347`  `手机qq扫一扫下方二维码，可直接申请加入哦~~`  

![qq群](./img/00/qq_group.jpg)


# swoole 内核剖析

#### 前言: [我为什么要进行swoole内核剖析](./00/00.why_write_it.md)

1. [swoole 环境要求](./00/01.environment.md)
2. [swoole 扩展安装](./00/02.install.md)
3. [一次小小的swoole内核之旅](./00/03.one_swoole_travel.md)

## 第一章 基本的数据结构

1. [字符串](./01/01.string.md)
2. [数组](./01/02.array.md)
3. [链表](./01/03.list.md)
4. 哈希表
5. 通道
6. 堆

## 第二章 内存管理器 - 内存池

1. [共享内存](./02/01.share_memory.md)
2. [固定内存](./02/02.fix_memory.md)
3. [全局内存](./02/03.global_memory.md)
4. [消息队列](./02/04.message_queue.md)
5. [缓冲](./02/05.buffer.md)

## 第三章 核心功能

1. [日志收集器](./03/01.log_collecter.md)
2. 反应堆
3. 进程池
4. 线程池
5. 锁
6. 管道

## 第四章 内核源码分析 - 服务器和客户端

1. server
2. client
3. http server
4. websocket server
5. redis服务器
6. mysql服务器

## 第五章 内核源码分析 - 进程

1. 进程的实现
2. 进程的优化

## 第六章 内核源码分析 - 异步io

1. 基本异步io [线程池的使用]
2. [定时器](./06/02.timer.md)
3. 事件循环

## 第七章 协程的实现
1. 协程的原理
2. swoole实现协程的基本过程
3. 内核分析

## 第八章：内核分析 - 其他
1. buffer的实现
2. table的实现
3. atomic的实现
4. mmap的实现
5. [时间轮算法](./08/05.time_wheel.md)

#### 后记：swoole内核分析的喜怒哀乐
