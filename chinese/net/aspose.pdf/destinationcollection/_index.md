---
title: "类 DestinationCollection"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.DestinationCollection 类。该类表示所有目标的集合，一个将名称字符串映射到目标的名称树，参见 PDF 文档中的 12.3.2.3 命名目标以及 7.7.4 名称字典。"
type: docs
weight: 3630
url: /zh/net/aspose.pdf/destinationcollection/
---
## DestinationCollection class

类表示 pdf 文档中所有目标的集合（一个将名称字符串映射到目标的名称树（参见 12.3.2.3，“Named Destinations”）以及（参见 7.7.4，“Name Dictionary”））。

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
| [GetEnumerator](../../aspose.pdf/destinationcollection/getenumerator/)() | 返回枚举器。 |
| [GetExplicitDestination](../../aspose.pdf/destinationcollection/getexplicitdestination/)(string, bool) | 通过名称返回显式目标。 |
| [GetPageNumber](../../aspose.pdf/destinationcollection/getpagenumber/)(string, bool) | 通过名称返回目标的 Page 编号。 |
| [IndexOf](../../aspose.pdf/destinationcollection/indexof/)(KeyValuePair&lt;string, object&gt;) | 返回集合中目标的索引。 |
| [Remove](../../aspose.pdf/destinationcollection/remove/)(KeyValuePair&lt;string, object&gt;) | 移除指定的项。集合是只读的。始终抛出 NotSupportedException 异常。 |

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


