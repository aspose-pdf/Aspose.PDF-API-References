---
title: Class AppearanceDictionary
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.AppearanceDictionary 类。注释外观字典指定注释在页面上如何以视觉方式呈现
type: docs
weight: 1490
url: /zh/net/aspose.pdf.annotations/appearancedictionary/
---
## AppearanceDictionary class

注释外观字典指定注释在页面上如何以视觉方式呈现。

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count/) { get; } | 获取字典中包含的元素数量。 |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize/) { get; } | 获取一个值，指示字典是否具有固定大小。 |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly/) { get; } | 获取一个值，指示字典是否为只读。 |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized/) { get; } | 获取一个值，指示对字典的访问是否是同步的（线程安全）。 |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item/) { get; set; } | 表示获取外观流的方便形式。 |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys/) { get; } | 获取字典的键。如果外观字典具有子字典，则 [`Keys`](./keys/) 包含 (N&#x7C;R&#x7C;D).state 值，其中 N - 正常外观，R - 悬停外观，D - 按下外观，state - 状态的名称（例如，复选框的 On、Off）。 |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot/) { get; } | 获取一个可以用于同步访问字典的对象。 |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values/) { get; } | 获取字典值的列表。结果集合包含 XForm 对象的列表。 |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add)(KeyValuePair&lt;string, XForm&gt;) | 将键值对添加到字典中。 |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add_2)(string, XForm) | 为指定的键添加 X 形式。 |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear/)() | 从字典中删除所有元素。 |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains/)(KeyValuePair&lt;string, XForm&gt;) | 检查指定的键值对是否包含在字典中。 |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey/)(string) | 确定此字典是否包含指定的键。 |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto)(XForm[], int) | 将字典的元素复制到数组，从特定数组索引开始。 |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator/)() | 返回字典的 IDictionaryEnumerator 对象。 |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove)(KeyValuePair&lt;string, XForm&gt;) | 从集合中删除键/值对。 |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove_1)(string) | 从字典中删除键。 |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue/)(string, out XForm) | 尝试在字典中查找键，如果找到则检索值。 |

### See Also

* class [XForm](../../aspose.pdf/xform/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)