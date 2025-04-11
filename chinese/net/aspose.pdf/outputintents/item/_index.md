---
title: OutputIntents.Item
second_title: Aspose.PDF for .NET API Reference
description: OutputIntents 属性。获取指定索引处的输出意图
type: docs
weight: 30
url: /zh/net/aspose.pdf/outputintents/item/
---
## OutputIntents 索引器

获取指定 *index* 处的输出意图。

```csharp
public OutputIntent this[int index] { get; }
```

| 参数 | 描述 |
| --- | --- |
| index | 要获取的输出意图的零基索引。 |

### 返回值

指定 *index* 处的输出意图。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *index* 小于 0 或 *index* 等于或大于 [`Count`](../count/)。 |
| InvalidOperationException | 包含集合的文档没有目录以访问 OutputIntents。 |

### 另请参见

* 类 [OutputIntent](../../outputintent/)
* 类 [OutputIntents](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)