# KeyCrafter

一. 介绍：<br>
====
该项目是一个基于java的key-value数据库。<br>

预计实现如下功能:<br>
----
1. 底层dict字典实现存储数据。<br>
  1.1 字典底层结构：<br>
    1.1.1 手搓链表，哈希表<br>
    1.1.2 实现哈希桶解决hash冲突问题<br>
  1.2 rehash 过程java重构， <br>
    1.2.1 实现rehash条件判断<br>
    1.2.2 渐进式rehash的实现，每次增删改查调用单步rehash。<br>
2. 底层 skiplist 实现存储list<br>
3. 实现基础 5 种数据类型的操作命令：String, Set, ZSet, Hash, List <br>
4. RDB 持久化实现，AOF重新实现<br>

二. 展望计划:<br>
====
1. 希望实现后续的stream，GEO， HyperLogLog等<br>
2. 希望实现主从复制，哨兵集群<br>
