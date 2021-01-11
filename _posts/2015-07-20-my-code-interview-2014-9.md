---
layout: post
title: "my interview experience"
description: ""
category: null
tags: 
---

# 2014年9月我的面试经历


## 百度 应聘经历



陈志韬 一面：2014年9月21日 

traceroute 实现方式



vector 数组 区别 list map unordered_map 



TCP 怎么控制阻塞的？



滑动窗口是做什么用？ 用来同步发送方和接收方的 发送速度的。



VFS 虚拟文件系统 是做什么的？



ARP攻击是什么？怎么防止，硬件绑定ip, MAC, 观察有谁发出的ARP特别多，封禁之。



进程间通信的机制



问面试官问题：软件开发工程师，写的要做的工作是算法什么的，到公司内部做什么？

这个职位是一个人才池，到公司后各个部门从里面选



5点面试，6点结束，7点多收到二面通知，感觉相当有效率





江霞：给你一个short数，让你转成一个低字节在低位，高字节在高位的byte数组

TCP三次握手。

1.项目，非常细，要讲清楚原理和具体的实现方法

2.const变量的作用，指针与引用的区别

3.数据库的隔离机制，select语句

4.TCP、UDP的区别以及各有什么优点, TCP三次握手

5.死锁是怎么回事，产生的必要条件，如何避免死锁，讲解银行家算法

6.C++多态是怎么回事，如何实现

7.N*N的格子，规定走向，到达最右下端顶点有多少种走法

8.算法题：一个short型数，把它变成低地址在前，高地址在后的byte型数组



张爱民

iptable  推荐学习pthread，socket



彭毅

数据库的组合与连接 怎么查询

3级台阶 走法计算



死锁、死锁避免方法；进程、线程同步；TCP/UDP； 指针、引用区别；数据库查找、联合查找



高帅：

逻辑地址如何转化成物理地址



如果给你一台linux系统

如何接受多个请求。。。

如果负载不下去 如何优化



建议看的书籍：

linux程序设计

unix网络编程

unix环境高级编程

posix多线程程序设计

debug hacks gdb



李成：

字符串的正则表达式匹配的代码



陈志韬 二面：2014年9月22日 

乱序数组，找出其中满足 左边数小于该数，右边数大于等于该数的 数



最近公共祖先LCA

https://github.com/julycoding/The-Art-Of-Programming-By-July/blob/master/ebook/zh/03.03.md



TCP3次握手 SYN Flood攻击是什么



Linux 编译后的文件有哪些内容？.text .data .bss 堆 栈

父进程 子进程关系  没有什么特殊的关系吗？

子进程可以访问父进程数据吗？

父进程占用10G内存，创建子进程后直接使用10G内存吗？ copy on write 这个时候访问需要锁吗，锁的机制是什么

进程间通讯机制？ 进程调度算法



线程可以访问进程的所有数据吗？ 可以访问哪些数据？



共享内存的实现机制



Linux文件系统inode节点存储哪些数据，inode与磁盘块的对应方式



什么是纯虚函数，写一个，纯虚函数占据空间大小，加上一个int后呢？再加一个char呢？

子类实现了一个父类的虚函数，然后又添加了一个虚函数，这个时候，子类和父类的虚表都是什么样子的？



findK 有哪些算法，这些算法的时间复杂度都是多少？ https://github.com/julycoding/The-Art-Of-Programming-By-July/blob/master/ebook/zh/02.01.md

1、quickselect



B树，B+树 介绍，B+树的叶子节点的存储方式

B-树



问面试官的问题：百度新员工的培训机制是什么样子的？

员工学院，2~3个月，自己从20多门课中选十几门课上，然后导师



王洋 测试 三面问题：

39个球一次取1-4个，两个人轮着取，最后取光的那个人获胜，设计方案，不能不取



算法是10亿个int 找所有相同的





2014年9月24日 百度三面

项目中最大的收获是什么

讲述Linux系统调用 有什么作用

中断和异常的区别



问了自己对未来要做什么的规划，还有想要做什么方向？



详述Linux read命令实现方式



火车运煤问题：http://coolshell.cn/articles/4429.html



## 小米笔试题



给你一个输入的两个字符串

(-2,4),(2,3),(5,0)

(-3,3),(2,2),(1,1)



分别代表两个多项式，求出多项式的乘积，并输出



拓扑排序



## 网易面试题 —— 张爱民



面试前的小笔试题：

     给一个无向图的定义，要求输出该图的连通子图的个数



面试一：

     C++基础：template和多态的区别，虚函数和函数重载的区别

     操作系统基础：死锁

     网络：TCP三次握手

     简单算法：

          栈来实现队列

          如何求出一个链表的中点

     其他算法：

     几何：

               如何判断一个点在一条直线左边，如何判断一个点在三角形内还是三角形外

     概率：

               一个数组，长为N，其前k个数组元素已经放到另一个小数组中，i从大数组的k+1位开始到n，以概率k/i随机替换小数组中的任一个数，问最后某个数字在小数组中的概率是多少？

               一个线段分为三个小段，问这三个小段可以组成一个三角形的概率是多少？

              



面试二：

算法：

     1.用随机生成0,1的随机数生成器生成[0-7]

     2.主角打空间里的怪，使子弹跑的距离最短

     3. 随机生成一个圆圈里的坐标，要求不需要判断这个生成的坐标是否越界

     4.空间中有N个点，求遍历所有点的最短距离

系统结构：

     1.死锁的硬件实现

其他：

     你编程碰到最大的问题是什么，如何解决的？



智能指针的实现


## 阿里面试题



李成阿里面试总结：一面：linux从基本命令问到文件系统到内存管理



c++：从模板的本质到算法的设计 kmp->rb->suffix-tree



二面：就是各种团队协作的东东了



c++：模板初始化，模板的本质


Linux命令，文件系统，内存管理，多态


C++和java的主要区别


周军蕊面试：

用户态、内核态区别

操作系统中 malloc、free的功能与实现方法


继承 优缺点  相对于组合

vector 优缺点 相对于 数组



Linux系统启动过程



## 涂鸦移动面试经历

September 16, 2014 

面试题：

strcmp实现

对学生成绩的排序 < 1000



给你一个长度为s的环形字符串，找出字典序最小的长度为s的子串       这类算法叫最小表示法

这个我没有答上来，算是KMP的一个变种





对移动游戏的看法



高帅被问的问题

希尔排序，二维数组一个点只能向上向右走，求总共有多少路径，



给出前序中序遍历，写出后序



## 腾讯应聘经历



进入腾讯 安全中心 的师兄 说的重点 

操作系统：

进程内存空间（.text段 .data .BSS 堆 栈）

死锁

进程通信（在于传输数据）

进程同步（在于呼哧访问资源）

中断



算法和数据结构：

STL map和红黑树，Hash_map

手写算法，快排，兄弟字符串

链表是否有环

语言（C++）/ 设计模式


C++对象，内存布局，虚表，多态

C++实现单例模式

以下两个我感觉是偏安全多一些

线程安全/可重入

调用约定 stdcall cdecl



## 美团应聘经历

美团笔试：


1、概率，红球

2、单链表整数相加

3、先递增 后递减 数组求最大

4、

5、汉字发音的全排列 

6、求n个点间的最小斜率

7、找出邻近数和最接近零的 连续子数组

8、寻找字符串中符合在字符串的该查询串的


李成

美团面试：Linux常用命令 、笔试的题目、线程与进程的区别 、个人规划、研究生期间做的最有成就感的事


美团面试是三轮一起面试，其实是不刷人的，感觉相当于三个同级别的人给你面试，从不同的角度观察你。


我的面试题：

Linux下777的目录A，下面的一个文件b.txt，权限为600，问我能对b.txt做什么操作？

查找二叉树路径和为固定值的路径，路径指从根节点到叶结点的节点值之和  递归的实现方式？

kmp算法

在2M个数中，找出前100个数，内存只能存200个数。  与堆相关？

找出n个位置不相同的点的斜率最大的两个点的图示证明，笔试题的延伸



最有成就感的事情



解释善于倾听，和知识面广（我简历上的内容）



进程间通信机制



## 搜狗应聘经历

二叉查找树 转换成 完全二叉查找树

一个对象的序列化

用socket模拟recv，send等操作

线程安全性，与 可重入性


以下是面试内容：


基数排序  计数排序 桶排序

findK实现

二进制字符串相加，注意空指针的计算


经历：

策略研究去应聘的人特别少，所以自己有优势，前一天晚上7点多电话通知，并聊了一会自己会什么。



第二天下午3点我去的面试

去之前感觉他对我的印象特别好，所以基本上没为难我就开始和我聊起来了，中间面试官在我做题的时候还打电话问他的boss咨询如何发offer，说有一个人特别好，一个人差点，2个人还行，不知道我属于哪一个。