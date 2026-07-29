---
title: "类 AppearanceDictionary"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Annotations.AppearanceDictionary 类。注释外观字典，指定注释在页面上如何以视觉方式呈现。"
type: docs
weight: 1580
url: /zh/net/aspose.pdf.annotations/appearancedictionary/
---
## AppearanceDictionary class

注释外观字典，指定注释在页面上如何以视觉方式呈现。

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count/) { get; } | 获取字典中包含的元素数量。 |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize/) { get; } | 获取指示字典是否具有固定大小的值。 |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly/) { get; } | 获取指示字典是否为只读的值。 |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized/) { get; } | 获取指示对字典的访问是否同步（线程安全）的值。 |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item/) { get; set; } | 表示获取外观流的便捷形式。 |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys/) { get; } | 获取字典的键。如果外观字典有子字典，则[`Keys`](./keys/) 包含 (N&#x7C;R&#x7C;D).state 值，其中 N 表示普通外观，R 表示悬停外观，D 表示按下外观，state 表示状态的名称（例如复选框的 On、Off）。 |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot/) { get; } | 获取可用于同步对字典访问的对象。 |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values/) { get; } | 获取字典值的列表。结果集合包含 XForm 对象的列表。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add)(KeyValuePair&lt;string, XForm&gt;) | 向字典中添加键和值对。 |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add_2)(string, XForm) | 为指定键添加 X 表单。 |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear/)() | 从字典中移除所有元素。 |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains/)(KeyValuePair&lt;string, XForm&gt;) | 检查字典中是否包含指定的键值对。 |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey/)(string) | 确定此字典是否包含指定的键。 |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto)(XForm[], int) | 将字典的元素复制到 Array 中，从特定的 Array 索引开始。 |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator/)() | 返回字典的 IDictionaryEnumerator 对象。 |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove)(KeyValuePair&lt;string, XForm&gt;) | 从集合中移除键/值对。 |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove_1)(string) | 从字典中移除键。 |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue/)(string, out XForm) | 尝试在字典中查找键并在找到时检索其值。 |

### 另请参见

* class [XForm](../../aspose.pdf/xform/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


