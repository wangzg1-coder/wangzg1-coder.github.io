---
layout: post
title: 我的第一篇 blog 学习笔记
---

## 为什么要学大数据？

今天我开始了 AI programming 的学习之旅。

### 核心代码演示

这是我学会的第一个 PySpark 代码：

```python
data = [("Alice", 1), ("Bob", 2)]
df = spark.createDataFrame(data, ["Name", "Age"])
df.show()
