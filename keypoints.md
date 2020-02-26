
## Java Core

- Java基本类型有哪些，所占字节和范围
- ArrayList与LinkedList的实现和区别
- 为什么Set，List，Map不实现Cloneable和Serializable接口
- Arrays.sort的实现
- 哪些集合类是线程安全的
- HashMap：内部实现，hash冲突如何解决，扩容时机，扩容如何避免rehash
- LinkedHashMap：内部实现，如何用它实现LRU（尾插法，活跃数据在尾部）
- TreeMap：内部实现，如何用它实现一致性Hash
- CopyOnWriteArrayList:了解COW机制，适用场景
- ConcurrentHashMap：不同jdk版本中的实现原理，扩容时做了什么优化，如何保证并发的同时提高性能，如何让多线程同时参与扩容
- BlockingQueue的四种实现LinkedBlockingQueue,ArrayBlockingQueue,DelayQueue,SynchronousQueue，每种具体是如何实现的
- 四种引用类型：强，软，弱，虚，各自的适用场景和释放机制
- volatile的使用
- java io库的整体架构和使用的设计模式
- session是什么，cookie的区别


## 并发和多线程

- synchronized：偏向锁，轻量级锁，重量级锁，锁升级的过程，与ReentrantLock的区别, synchronized 的实现原理,monitor对象
- ReentrantLock如何实现公平锁和非公平锁
- AtomicInteger的实现原理：
- CAS的适用场景，CAS的实现原理，如何实现乐观锁
- 乐观锁和悲观锁的区别
- AQS是什么，内部实现是什么，相关的ReentrantLock, Semphore,CounDownLatch, CylicBarrier的实现，AQS是如何唤醒下一个线程的
- CountDownLatch , CylicBarrier区别，各自用在什么场景
- ThreadLocal的实现，应用场景，内存泄露问题
- ThreadPoolExecutor的工作原理及几个重要参数，往线程池里提交一个任务会发生，线程池的非核心线程什么时候会被释放
- 如何排查死锁



## JVM

- 类加载机制的步骤，static和final的成员变量加载时机
- 双亲委派模型，如何自己实现一个classloader来打破双亲委派
- 垃圾回收原理
- 几种常见的垃圾回收器的特征，CMS和G1垃圾回收过程
- CMS GC回收分为哪几个阶段，分别做了什么，CMS有哪些重要参数，CMS的优点缺点
- jvm的内存划分
- 为什么要划分年轻代，老年代，年轻代为啥采用复制算法，老年代为啥采用标记清除，标记整理算法
- 什么情况下使用堆外内存，如何被回收
- 什么情况下年轻代溢出，什么情况下老年代溢出

## 线上问题排查 
- 频繁full gc，如何排查


## IO

- BIO,NIO区别，多路复用机制
- 同步阻塞，同步非阻塞，异步的区别
- select，poll，epoll的区别
- reactor线程模型是什么
- proactor模型是什么


## 网络
- http报文的结构和内容
- 三次握手，四次挥手步骤，SYN攻击，time_wait问题， 2msl



## Spring

- bean的生命周期，循环依赖问题
- AOP的实现
- interceptor是什么，与aop的区别是什么
- spring事物传播机制
- java动态代理，cglib动态代理区别，spring使用何种方式







## Dubbo

- 说下Dubbo的实现：服务发现，路由，异步调用，限流降级，失败重试
- 如何做负载均衡
- 如何做限流降级
- 如何优雅下线
- 如何实现异步调用

## Netty
- netty底层实现
- io模型
- channelpipeline的实现和原理


## Kafka
- 原理和容错

## RPC
- 常见序列化协议及其特点 （thrift，avro, protobuf）
- 



## RocketMQ

- 如何保证高可用
- 如何保证高吞吐
- 消息是否有序
- 消息的局部顺序如何保证
- 事务消息的实现机制
- 推模型还是拉模型





## Redis

- 性能为什么高
- 单线程的redis如何利用多核CPU
- 缓存淘汰策略
- 如何持久化数据
- 有哪几种数据结构
- 集群有哪几种形式
- 如何保证redis和数据库DB的数据一致性？？
- 缓存穿透是什么，如何解决
- 缓存雪崩时啥，如何解决
- 如何用redis实现分布式锁
- memcached内存原理，为什么是基于块的存储











## MySQL

- 事务隔离级别
- 锁，索引的数据结构
- 聚簇索引，非聚簇索引是什么
- 最左匹配原则
- 查询优化explain
- 行锁，表锁，间隙锁，意向锁是什么
- 为什么使用B+树，不用B树，红黑树
- 分库分表如何选择分表键，分库分表时，查询时一般如何做排序
- 





## Zookeeper

- 原理
- 如何实现分布式锁，与redis分布式锁相比，优点缺点
- 



## Nginx
- 怎么实现负载均衡




## HBase

- 适用的场景，与Cassandra的区别
- 架构图是什么
- 查数据，读数据的流程
- 写数据的流程



## 设计模式
- 单例模式：懒汉，饿汉，双重校验，内部类，枚举
- 代理模式
- 适配器模式
- 装饰者模式
- 观察者模式
- 策略模式
- 外观模式
- 命令模式
- 创建者模式
- 抽象工厂模式



## Linux常用命令
- 统计 wc -l
- 排序 sort?
- 前几 head
- awk，cat，sort，cut，grep，qniq，wc，top



## 算法
- ip问题，如何判断ip是否在多个ip段中
- 判断数组两个中任意两个数之和是否为给定的值
- 写一段代码，实现死锁
- 常用排序算法（选择，插入）,二分查找
- LRU算法实现

















 