# 第一章 mysql逻辑架构

### 并发控制

* 读写锁 （共享锁和排它锁）
* 锁粒度 ：表锁 行锁
* 事务：原子性 一致性 隔离性 持久性  acid
* 隔离级别：未提交读；提交读；可重复读；可串行化

![image-20210908212247836](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20210908212247836.png)

* 死锁：两个或者多个事务在统一资源上相互占用，并请求锁定对方占用的资源，从而导致恶性循环的现象。