---
title: 数据库系统：从单机内核到分布式一致性
linkTitle: 电子书
description: 从文件存储逐步走向数据库内核、复制和分布式共识。
type: book
book_kind: book
sidebar_root_for: self
sidebar_root_link_self: true
outputs: [HTML, print, markdown]
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

## 目录 {#contents}

{{< book-toc depth=2 >}}

## 怎样使用本书

先停在每章的“尝试”处自己推演，再读概念和实现联系。做完章节练习后，用[学习路线](learning-path/)重建概念依赖；[概念演化图](evolution-map/)记录每个抽象的压力来源；[掌握协议](learning-protocol/)说明如何用解释、推导、应用和重建检查理解。
