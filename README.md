# 2021年最新整理，5000道校招常用面试题，包含leetcode，校招笔试题，面试题，算法题，语法题。（2021/06/28开始）每天持续更新中。。。
* [ACM](#1)
* [算法题](#2)
* [leetcode](#3)
* [mysql](#4)
* [redis](#5)
* [nginx](#6)
* [语法语言](#7)
* [网络原理](#8)
* [网络编程](#9)
* [操作系统](#10)
* [编译原理](#11)
* [内存](#12)
* [磁盘](#13)
* [并发](#14)
* [链表、堆与栈](#15)
* [树型结构](#16)
* [图](#17)
* [排序](#18)
* [字符串](#19)
* [基础组件](#20)
* [云原生](#21)
* [顺利通过校招](#22)


<h3 id="1">ACM</h3> 

---
##### [1.计蒜客：置换的玩笑（DFS）](https://github.com/0voice/campus_recruitmen_questions/blob/main/ACM/%E8%AE%A1%E8%92%9C%E5%AE%A2%EF%BC%9A%E7%BD%AE%E6%8D%A2%E7%9A%84%E7%8E%A9%E7%AC%91%EF%BC%88DFS%EF%BC%89.cpp)

##### 2.整数的划分
##### 3.DP+四边形不等式优化（hdu 3506 Monkey Party）
##### 4.快餐（hoj 1005 fast food）
##### 5.hoj 1031完全背包Piggy-Bank
##### 6.数字金字塔（hoj 1058Number Triangles）
##### 7.肥猫的表亲（hoj 1061Fat Cat's cousin II）
##### 8.加建楼梯（hoj 1090The Staircases）
##### 9.公共子序列（hoj 1227 Common Subsequence）
##### 10.桥接的信号（hoj 1288 Bridging Signals）



<br>

<h3 id="2">算法题</h3> 

---

<br>

<h3 id="3">leetcode</h3> 

---

<br>

<h3 id="4">mysql</h3> 

---
##### 1. MySQL 索引使用有哪些注意事项呢？	
##### 2. MySQL 遇到过死锁问题吗，你是如何解决的？	
##### 3. 日常工作中你是怎么优化SQL的？	
##### 4. 说说分库与分表的设计	
##### 5. InnoDB与MyISAM的区别	
##### 6. 数据库索引的原理，为什么要用 B+树，为什么不用二叉树？	
##### 7. 聚集索引与非聚集索引的区别	
##### 8. limit 1000000 加载很慢的话，你是怎么解决的呢？	
##### 9. 如何选择合适的分布式主键方案呢？	
##### 10. 事务的隔离级别有哪些？MySQL的默认隔离级别是什么？	
##### 11. 什么是幻读，脏读，不可重复读呢？	
##### 12. 在高并发情况下，如何做到安全的修改同一行数据？	
##### 13. 数据库的乐观锁和悲观锁。	
##### 14. SQL优化的一般步骤是什么，怎么看执行计划（explain），如何理解其中各个字段的含义。	
##### 15. select for update有什么含义，会锁表还是锁行还是其他。	
##### 16. MySQL事务得四大特性以及实现原理	
##### 17. 如果某个表有近千万数据，CRUD比较慢，如何优化。
##### 18. 如何写sql能够有效的使用到复合索引。
##### 19. mysql中in 和exists的区别。
##### 20. 数据库自增主键可能遇到什么问题。	
##### 21. MVCC熟悉吗，它的底层原理？	
##### 22. 数据库中间件了解过吗，sharding jdbc，mycat？	
##### 23. MYSQL的主从延迟，你怎么解决？	
##### 24. 说一下大表查询的优化方案	
##### 25. 什么是数据库连接池?为什么需要数据库连接池呢?	
##### 26. 一条SQL语句在MySQL中如何执行的？	
##### 27. InnoDB引擎中的索引策略，了解过吗？	
##### 28. 数据库存储日期格式时，如何考虑时区转换问题？	
##### 29. 一条sql执行过长的时间，你如何优化，从哪些方面入手？	
##### 30. MYSQL数据库服务器性能分析的方法命令有哪些?	
##### 31. Blob和text有什么区别？	
##### 32. mysql里记录货币用什么字段类型比较好？	
##### 33. Mysql中有哪几种锁，列举一下？	
##### 34. Hash索引和B+树区别是什么？你在设计索引是怎么抉择的？	
##### 35. mysql 的内连接、左连接、右连接有什么区别？	
##### 36. 说说MySQL 的基础架构图	
##### 37. 什么是内连接、外连接、交叉连接、笛卡尔积呢？	
##### 38. 说一下数据库的三大范式	
##### 39. mysql有关权限的表有哪几个呢？	
##### 40. Mysql的binlog有几种录入格式？分别有什么区别？	
##### 41. InnoDB引擎的4大特性，了解过吗	
##### 42. 索引有哪些优缺点？	
##### 43. 索引有哪几种类型？	
##### 44. 创建索引有什么原则呢？	
##### 45. 创建索引的三种方式	
##### 46. 百万级别或以上的数据，你是如何删除的？
##### 47. 什么是最左前缀原则？什么是最左匹配原则？
##### 48. B树和B+树的区别，数据库为什么使用B+树而不是B树？
##### 49. 覆盖索引、回表等这些，了解过吗？
##### 50. B+树在满足聚簇索引和覆盖索引的时候不需要回表查询数据？
##### 51. 何时使用聚簇索引与非聚簇索引	
##### 52. 非聚簇索引一定会回表查询吗？	
##### 53. 组合索引是什么？为什么需要注意组合索引中的顺序？	
##### 54. 什么是数据库事务？	
##### 55. 隔离级别与锁的关系	
##### 56. 按照锁的粒度分，数据库锁有哪些呢？锁机制与InnoDB锁算法	
##### 57. 从锁的类别角度讲，MySQL都有哪些锁呢？	
##### 58. MySQL中InnoDB引擎的行锁是怎么实现的？	
##### 59. 什么是死锁？怎么解决？	
##### 60. 为什么要使用视图？什么是视图？	
##### 61. 视图有哪些特点？哪些使用场景？	
##### 62. 视图的优点，缺点，讲一下？	
##### 63. count(1)、count(*) 与 count(列名) 的区别？	
##### 64. 什么是游标？	
##### 65. 什么是存储过程？有哪些优缺点？	
##### 66. 什么是触发器？触发器的使用场景有哪些？	
##### 67. MySQL中都有哪些触发器？	
##### 68. 超键、候选键、主键、外键分别是什么？	
##### 69. SQL 约束有哪几种呢？	
##### 70. 谈谈六种关联查询，使用场景。	
##### 71. varchar(50)中50的涵义	
##### 72. mysql中int(20)和char(20)以及varchar(20)的区别	
##### 73. drop、delete与truncate的区别	
##### 74. UNION与UNION ALL的区别？	
##### 75. SQL的生命周期？	
##### 76. 一条Sql的执行顺序？	
##### 77. 列值为NULL时，查询是否会用到索引？	
##### 78. 关心过业务系统里面的sql耗时吗？统计过慢查询吗？对慢查询都怎么优化过？	
##### 79. 主键使用自增ID还是UUID，为什么？	
##### 80. mysql自增主键用完了怎么办？	
##### 81. 字段为什么要求定义为not null？	
##### 82. 如果要存储用户的密码散列，应该使用什么字段进行存储？
##### 83. Mysql驱动程序是什么？
##### 84. 如何优化长难的查询语句？有实战过吗？
##### 85. 优化特定类型的查询语句
##### 86. MySQL数据库cpu飙升的话，要怎么处理呢？
##### 87. 读写分离常见方案？
##### 88. MySQL的复制原理以及流程	
##### 89. MySQL中DATETIME和TIMESTAMP的区别
##### 90. Innodb的事务实现原理？
##### 91. 谈谈MySQL的Explain	
##### 92. Innodb的事务与日志的实现方式	
##### 93. MySQL中TEXT数据类型的最大长度	
##### 94. 500台db，在最快时间之内重启。	
##### 95. 你是如何监控你们的数据库的？你们的慢日志都是怎么查询的？	
##### 96. 你是否做过主从一致性校验，如果有，怎么做的，如果没有，你打算怎么做？	
##### 97. 你们数据库是否支持emoji表情存储，如果不支持，如何操作？	
##### 98. MySQL如何获取当前日期？	
##### 99. 一个6亿的表a，一个3亿的表b，通过外间tid关联，你如何最快的查询出满足条件的第50000到第50200中的这200条数据记录。	
##### 100. Mysql一条SQL加锁分析	

<br>

<h3 id="5">redis</h3> 

---
##### 1、什么是 Redis?简述它的优缺点?
##### 2、Redis相比memcached有哪些优势?
##### 3、Redis支持哪几种数据类型?
##### 4、Redis主要消耗什么物理资源?
##### 5、Redis 的全称是什么?
##### 6、Redis有哪几种数据淘汰策略?
##### 7、Redis官方为什么不提供Windows版本?
##### 8、一个字符串类型的值能存储最大容量是多少?
##### 9、为什么Redis需要把所有数据放到内存中?
##### 10、Redis 集群方案应该怎么做?都有哪些方案?
##### 11、Redis 集群方案什么情况下会导致整个集群不可用?
##### 12、MySQL 里有 2000w 数据，redis 中只存 20w 的数据，如何保证 redis中的数据都是热点数据？
##### 13、Redis有哪些适合的场景?
##### 14、Redis.支持的Java客户端都有哪些?官方推荐用哪个?
##### 15、Redis 和Redisson有什么关系?
##### 16、Jedis与 Redisson对比有什么优缺点?
##### 17、Redis如何设置密码及验证密码?
##### 18、说说 Redis 哈希槽的概念?
##### 19、Redis 集群的主从复制模型是怎样的?
##### 20、Redis集群会有写操作丢失吗?为什么?
##### 21、Redis 集群之间是如何复制的?
##### 22、Redis 集群最大节点个数是多少?
##### 23、Redis 集群如何选择数据库?
##### 24、怎么测试Redis的连通性?
##### 25、Redis 中的管道有什么用?
##### 26、怎么理解 Redis 事务?
##### 27、Redis事务相关的命令有哪几个?
##### 28、Redis key的过期时间和永久有效分别怎么设置?
##### 29、Redis 如何做内存优化?
##### 30、Redis回收进程如何工作的?
##### 31、Redis回收使用的是什么算法?
##### 32、Redis 如何做大量数据插入?
##### 33、为什么要做Redis分区?
##### 34、有哪些Redis分区实现方案?
##### 35、Redis分区有什么缺点?
##### 36、Redis 持久化数据和缓存怎么做扩容？如果 Redis 被当做缓存使用，使用一致性哈希实现动态扩容缩容
##### 37、分布式Redis.是前期做还是后期规模上来了再做好?为什么?
##### 38、Twemproxy是什么?
##### 39、支持一致性哈希的客户端有哪些?
##### 40、Redis与其他 key-value存储有什么不同?
##### 41、Redis的内存占用情况怎么样?
##### 42、都有哪些办法可以降低Redis的内存使用情况呢?
##### 43、查看Redis使用情况及状态信息用什么命令?
##### 44、Redis 的内存用完了会发生什么?
##### 45、Redis是单线程的，如何提高多核CPU的利用率?
##### 46、一个 Redis 实例最多能存放多少的keys？List、Set、Sorted Set 他们最多能存放多少元素？
##### 47、Redis 常见性能问题和解决方案?
##### 48、Redis提供了哪几种持久化方式?
##### 49、如何选择合适的持久化方式?
##### 48、Redis提供了哪几种持久化方式?
##### 49、如何选择合适的持久化方式?
##### 50、修改配置不重启 Redis 会实时生效吗？

<br>

<h3 id="6">nginx</h3> 

---

<br>

<h3 id="7">语言语法</h3> 

---

<br>

<h3 id="8">网络原理</h3> 

---
##### 1.如何理解 URI？
##### 2.解释一下HTTP的超文本传输协议
##### 3.HTTP 的特点？HTTP 有哪些缺点？
##### 4.HTTP 报文结构是怎样的？
##### 5.如何理解 HTTP 的请求方法？
##### 6.http 常见字段有哪些？
##### 7.对于定长和不定长的数据，HTTP 是怎么传输的？
##### 8.HTTP 如何处理大文件的传输？
##### 9.HTTP 中如何处理表单数据的提交？
##### 10.如何理解 HTTP 代理？
##### 11.说说 HTTP1.1 相比 HTTP1.0 提高了什么性能？
##### 12.那上面的 HTTP1.1 的性能瓶颈，HTTP2 做了什么优化？
##### 13.HTTP2 有哪些缺陷？HTTP3 做了哪些优化？
##### 14.HTTP 与 HTTPS 有哪些区别？
##### 15.HTTPS 解决了 HTTP 的哪些问题？
##### 16.HTTPS 是如何解决上面的三个风险的？
##### 17.HTTPS 是如何建立连接的？其间交互了什么？
##### 18.UDP 和 TCP 的区别
##### 19.TCP 三次握手和四次挥手
##### 20.说说TCP传输的三次握手四次挥手策略
##### 21.什么是无状态协议，HTTP 是无状态协议吗，怎么解决
##### 22.OSI与TCP/IP各层的结构与功能,都有哪些协议?
##### 23.TCP协议如何保证可靠传输
##### 24.说说ARQ协议
##### 25.什么是滑动窗口和流量控制
##### 26.什么是拥塞控制
##### 27.在浏览器中输入url地址 ->> 显示主页的过程？
##### 28.HTTP长连接,短连接
##### 29.Cookie的作用是什么?和Session有什么区别？
##### 30.URI和URL的区别是什么?
##### 31.HTTP常见的状态码有哪些？
##### 32.说说常见的常见HTTP首部字段？
##### 33.HTTPS方式与web服务器通信的步骤？
##### 34.HTTP请求报文与响应报文格式？
##### 35.地址栏输入 URL 发生了什么？
##### 36.HTTPS的工作原理

<br>

<h3 id="9">网络编程</h3> 

---

<br>

<h3 id="10">操作系统</h3> 

---
##### 1、什么是操作系统？
##### 2、什么是系统调用？
##### 3、进程和线程的区别？
##### 4、进程有哪几种状态?
##### 5、进程间的通信方式
##### 6、线程间的同步的方式
##### 7、进程的调度算法
##### 8、操作系统的内存管理主要是做什么？
##### 9、常见的几种内存管理机制
##### 10、快表和多级页表
##### 11、分页机制和分段机制的共同点和区别
##### 12、逻辑(虚拟)地址和物理地址
##### 13、CPU 寻址了解吗?为什么需要虚拟地址空间?
##### 14、什么是虚拟内存(Virtual Memory)?
##### 15、局部性原理
##### 16、虚拟存储器
##### 17、虚拟内存的技术实现
##### 18、页面置换算法


<br>

<h3 id="11">编译原理</h3> 

---

<br>

<h3 id="12">内存</h3> 

---

<br>

<h3 id="13">磁盘</h3> 

---

<br>

<h3 id="14">并发</h3> 

---
##### 1.线程和进程区别
##### 2.创建线程的四种方式
##### 3.as-if-serial规则和happens-before规则的区别
##### 4.多线程如何使用？
##### 5.启动多线程调用使用什么方法？
##### 6.并发容器之CopyOnWriteArrayList详解
##### 7.并发容器之ThreadLocal详解
##### 8.并发容器之ConcurrentHashMap详解(JDK1.8版本)与源码分析
##### 9.并发容器之BlockingQueue详解
##### 10.ThreadLocal内存泄漏分析与解决方案

<br>

<h3 id="15">链表  、堆与栈</h3> 

---

<br>

<h3 id="16">树型结构</h3> 

---

<br>

<h3 id="17">图</h3> 

---

<br>

<h3 id="18">排序</h3> 

---

<br>

<h3 id="19">字符串</h3> 

---

<br>

<h3 id="20">基础组件</h3> 

---

<br>

<h3 id="21">云原生</h3> 

---

<br>

<h3 id="22">顺利通过校招</h3> 

---

**每天晚上8点免费技术分享直播，扫码即可加入【wx:cz1625358265】，小姐姐给你发每天的直播链接，备注github+校招笔试题** <br/>
**秋招学习内容：面试技巧、简历制作、企业选择等面试痛点问题分享** <br>
**常规直播内容：C/C++，Linux，Nginx，ZeroMQ，MySQL，Redis，fastdfs，MongoDB，ZK，流媒体，CDN，P2P，K8S，Docker，TCP/IP，协程，DPDK等等多个知识点技术分享**

![image](contact.jpg)









