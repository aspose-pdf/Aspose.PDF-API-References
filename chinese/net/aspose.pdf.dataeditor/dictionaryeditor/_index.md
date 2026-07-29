---
title: "类 DictionaryEditor"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.DataEditor.DictionaryEditor 类。一个用于访问文档树字典、文档字典、页面字典、资源字典的类。"
type: docs
weight: 3590
url: /zh/net/aspose.pdf.dataeditor/dictionaryeditor/
---
## DictionaryEditor class

用于访问文档树字典（文档字典、页面字典、资源字典）的类。

```csharp
public class DictionaryEditor : IDictionary<string, ICosPdfPrimitive>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DictionaryEditor](dictionaryeditor/#constructor)(Document) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_1)(Page) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_2)(Resources) |  |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/dictionaryeditor/allkeys/) { get; } | 完整的键集合。包含可编辑和不可编辑的键。 |
| [Count](../../aspose.pdf.dataeditor/dictionaryeditor/count/) { get; } | 获取 `DictionaryEditor` 中包含的元素数量。 |
| [IsReadOnly](../../aspose.pdf.dataeditor/dictionaryeditor/isreadonly/) { get; } | 获取一个值，指示 `DictionaryEditor` 是否为只读。 |
| [Item](../../aspose.pdf.dataeditor/dictionaryeditor/item/) { get; set; } | 获取或设置具有指定键的元素。 |
| [Keys](../../aspose.pdf.dataeditor/dictionaryeditor/keys/) { get; } | 可编辑键的集合。 |
| [Values](../../aspose.pdf.dataeditor/dictionaryeditor/values/) { get; } | 获取包含 `DictionaryEditor` 中值的 ICollection。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | 将 [`ICosPdfPrimitive`](../icospdfprimitive/) 设置到字典中。 |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add_1)(string, ICosPdfPrimitive) | 将 [`ICosPdfPrimitive`](../icospdfprimitive/) 设置到字典中。 |
| [Clear](../../aspose.pdf.dataeditor/dictionaryeditor/clear/)() | 从 `DictionaryEditor` 中移除所有项。 |
| [Contains](../../aspose.pdf.dataeditor/dictionaryeditor/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | 确定 `DictionaryEditor` 是否包含特定值。 |
| [ContainsKey](../../aspose.pdf.dataeditor/dictionaryeditor/containskey/)(string) | 确定 `DictionaryEditor` 是否包含具有指定键的元素。 |
| [CopyTo](../../aspose.pdf.dataeditor/dictionaryeditor/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/dictionaryeditor/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | 从 `DictionaryEditor` 中移除特定对象的第一次出现。 |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove_1)(string) | 从 `DictionaryEditor` 中移除具有指定键的元素。 |
| [TryGetValue](../../aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/)(string, out ICosPdfPrimitive) | 用于访问字符串、名称、布尔值、数字等简单数据类型。对其他类型返回 null。 |

### 另请参见

* interface [ICosPdfPrimitive](../icospdfprimitive/)
* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)


