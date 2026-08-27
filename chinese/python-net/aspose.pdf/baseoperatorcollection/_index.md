---
title: "BaseOperatorCollection"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示运算符集合的基类。"
type: docs
weight: 70
url: /zh/python-net/aspose.pdf/baseoperatorcollection/
---

## BaseOperatorCollection class

表示运算符集合的基类。

BaseOperatorCollection 类型公开以下成员：
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
| suppress_update() | 抑制内容数据的更新。<br/>            在调用 ResumeUpdate 之前，内容流不会被更新。 |
| resume_update() | 恢复文档更新。<br/>            如有挂起的更改，更新内容流。 |
| insert(index, op) | 在集合中插入运算符。 |
| cancel_update() | 取消上一次更新。<br/>            当更改不应触发内容更新时，可调用此方法。 |

### 另请参阅

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

