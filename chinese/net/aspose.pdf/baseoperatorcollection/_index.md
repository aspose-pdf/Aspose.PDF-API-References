---
title: Class BaseOperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.BaseOperatorCollection class. 表示操作符集合的基类
type: docs
weight: 2830
url: /zh/net/aspose.pdf/baseoperatorcollection/
---
## BaseOperatorCollection class

表示操作符集合的基类。

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## Properties

| Name | Description |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | 获取集合中操作符的数量。 |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | 指示集合是否仅限于快速文本提取 |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | 如果集合是只读的，则返回 true。 |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | 通过索引获取操作符。 |

## Methods

| Name | Description |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | 将新操作符添加到集合中。 |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | 取消最后一次更新。此方法可以在更改不应引发内容更新时调用。 |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | 清空集合。 |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | 检查操作符是否存在于集合中。 |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | 将操作符复制到操作符列表中。 |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | 返回集合的枚举器 |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | 将操作符插入集合中。 |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | 从集合中移除操作符。 |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | 恢复文档更新。如果有任何待处理更改，则更新内容流。 |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | 抑制更新内容数据。在调用 ResumeUpdate 之前，内容流不会更新。 |

### See Also

* class [Operator](../operator/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)