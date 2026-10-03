---
title: 数据库系统：从单机内核到分布式一致性
linkTitle: 电子书
description: 从文件存储逐步走向数据库内核、复制和分布式共识。
type: book
book_kind: book
sidebar_root_for: self
sidebar_root_link_self: true
outputs: [HTML, print, markdown]
sidebar_headings: false
no_list: true
menus:
  main:
    identifier: book
    weight: 10
cascade:
  type: book
  footer_style: slim
  sidebar_headings: 3
---

这本书从一个朴素的问题开始：怎样可靠保存记录并快速查回？每一章沿着“问题 → 旧方法 → 限制 → 发现 → 新能力 → 新问题”展开。路线是认知上的重建，不是数据库技术史。

## 阅读目录

先停在每章的“尝试”处自己推演，再读概念和实现联系。读完一章后，沿着它留下的新问题继续向下。

### 起点

- [序言｜把数据库知识学成可以重建的东西](preface/) — 认识这套教程的学习方法。
{.cards}

### 第一阶段：数据怎样落盘，又怎样找到？

- [01 · 从文件到存储页](ch01-storage/) — 从追加记录开始，推导页为什么成为存储和缓存的单位。
- [02 · 怎样少读页？从索引到 B+ 树](ch02-indexes/) — 从全表扫描出发，推导索引与多路导航结构。
{.cards}

### 第二阶段：查询怎样变成执行过程？

- [03 · SQL 怎样变成执行计划？](ch03-query-plan/) — 看数据库怎样把声明式查询变为可选择、可估算的执行步骤。
{.cards}

### 学习地图

- [学习路线](learning-path/) — 查看已经完成的章节和后续演化阶段。
- [概念演化图](evolution-map/) — 追踪每个抽象由什么问题逼出。
- [学习协议](learning-protocol/) — 用解释、推导、应用和重建检查理解。
{.cards}
