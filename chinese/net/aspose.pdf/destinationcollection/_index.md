---
title: Class DestinationCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DestinationCollection 类。该类表示所有目标的集合（一个名称树将名称字符串映射到目标，见 12.3.2.3 “命名目标”，见 7.7.4 “名称字典”）在 PDF 文档中。
type: docs
weight: 3510
url: /zh/net/aspose.pdf/destinationcollection/
---
## DestinationCollection 类

该类表示所有目标的集合（一个名称树将名称字符串映射到目标（见 12.3.2.3，“命名目标”）和（见 7.7.4，“名称字典”））在 PDF 文档中。

```csharp
public sealed class DestinationCollection : ICollection<KeyValuePair<string, object>>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.pdf/destinationcollection/count/) { get; } | 获取集合中包含的元素数量。 |
| [IsReadOnly](../../aspose.pdf/destinationcollection/isreadonly/) { get; } | 获取一个值，指示集合是否为只读。 |
| [Item](../../aspose.pdf/destinationcollection/item/) { get; } | 通过索引获取目标对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.pdf/destinationcollection/add/)(KeyValuePair&lt;string, object&gt;) | 添加指定的项。集合是只读的。始终抛出 NotSupportedException 异常。 |
| [Clear](../../aspose.pdf/destinationcollection/clear/)() | 集合是只读的。始终抛出 NotSupportedException 异常。 |
| [Contains](../../aspose.pdf/destinationcollection/contains/)(KeyValuePair&lt;string, object&gt;) | 确定此实例是否包含该对象。 |
| [CopyTo](../../aspose.pdf/destinationcollection/copyto/)(KeyValuePair&lt;string, object&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/destinationcollection/getenumerator/)() | 返回枚举数。 |
| [GetExplicitDestination](../../aspose.pdf/destinationcollection/getexplicitdestination/)(string, bool) | 通过名称返回显式目标。 |
| [GetPageNumber](../../aspose.pdf/destinationcollection/getpagenumber/)(string, bool) | 通过名称返回目标的页码。 |
| [IndexOf](../../aspose.pdf/destinationcollection/indexof/)(KeyValuePair&lt;string, object&gt;) | 返回集合中目标的索引。 |
| [Remove](../../aspose.pdf/destinationcollection/remove/)(KeyValuePair&lt;string, object&gt;) | 移除指定的项。集合是只读的。始终抛出 NotSupportedException 异常。 |

### 另请参阅

* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)