# 数据库系统：从单机内核到分布式一致性

一套用 evo-learn 方法编写的中文电子书：从文件和存储页出发，逐步推导索引、查询执行、事务恢复、并发控制、MVCC，再走向复制、分布式共识和 TiDB。

## 阅读

电子书源文件位于 `content/book/`。书籍目录本身决定阅读顺序，章节号由 OINK 的 `book_number` 明确标注。首页区分已完成的内容和后续规划。

## 本地预览

需要 Go 1.27.0 和 Hugo Extended 0.165.0。项目通过 `go.mod` / `go.sum` 固定 OINK 主题版本；首次构建需要联网下载 Hugo 模块。

```bash
hugo server
```

严格生产构建：

```bash
hugo --cleanDestinationDir --gc --minify --environment production \
  --printPathWarnings --panicOnWarning
```

详细配置见 [hugo.yaml](hugo.yaml)；概念演化图、学习路线和掌握协议也都收录在书籍导航中。
