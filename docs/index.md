# 数据库系统：从单机内核到分布式一致性

一条从具体问题出发，逐步重建数据库内核与分布式系统的学习路线。我们不先罗列组件，而是追问：旧办法在哪些输入、负载或故障下失效？新的结构为何必要？

**[从序言开始](book/00-preface.md){ .md-button .md-button--primary }**
**[查看完整学习路线](SUMMARY.md){ .md-button }**

## 现在开始

从持久化记录开始，沿着页、索引、查询执行、日志恢复、并发控制和 MVCC，逐步走向复制、共识与分布式 SQL。实现对照覆盖 MySQL 8/InnoDB、PostgreSQL 和 TiDB，并区分通用原理与具体版本的实现事实。

## 当前内容

**阶段 1 · 从文件到索引**

[序言](book/00-preface.md) · [存储页](book/01-from-files-to-storage.md) · [索引与 B+ 树](book/02-indexes-and-btrees.md)

配套内容：[学习路线](SUMMARY.md) · [学习协议](curriculum.md) · [概念演化图](evolution-map.md)

## 学习方式

每章先提出问题，留出尝试空间，再展示旧方法的边界、关键观察、概念和推导。练习覆盖解释、推导、应用与重建。请在查看章末小结前，先试着从问题重走一次推导。
