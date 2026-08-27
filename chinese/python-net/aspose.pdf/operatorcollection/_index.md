---
title: "OperatorCollection"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "类表示运算符的集合"
type: docs
weight: 1010
url: /zh/python-net/aspose.pdf/operatorcollection/
---

## OperatorCollection class

类表示运算符的集合

OperatorCollection 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| is_fast_text_extraction_mode | 指示集合是否限制为快速文本提取。 |
## Indexer
| 名称 | 描述 |
| :- | :- |
| [index] | 通过索引获取运算符。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| insert(index, op) | 在集合中插入运算符。 |
| insert(at, ops) | 在给定位置插入运算符。 |
| insert(at, ops) | 在集合中插入运算符。 |
| delete(index) | 从集合中删除运算符。 |
| delete(ops) | 从集合中删除运算符。 |
| delete(list) | None |
| add(ops) | 在内容运算符的末尾添加运算符。 |
| add(ops) | 向集合中添加新运算符。 |
| suppress_update() | 抑制内容数据的更新。<br/>            在调用 ResumeUpdate 之前，内容流不会被更新。 |
| resume_update() | 恢复文档更新。<br/>            如有挂起的更改，更新内容流。 |
| cancel_update() | 取消上一次更新。<br/>            当更改不应触发内容更新时，可调用此方法。 |
| accept(visitor) | 接受 IOperatorSelector 访问者对象来处理运算符。 |
| replace(operators) | 用其他运算符替换集合中的运算符。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

