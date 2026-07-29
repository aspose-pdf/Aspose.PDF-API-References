---
title: "类 CosPdfDictionary"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.DataEditor.CosPdfDictionary 类。用于访问对象字典的类"
type: docs
weight: 3540
url: /zh/net/aspose.pdf.dataeditor/cospdfdictionary/
---
## CosPdfDictionary class

用于访问对象字典的类。

```csharp
public class CosPdfDictionary : CosPdfPrimitive, IDictionary<string, ICosPdfPrimitive>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CosPdfDictionary](cospdfdictionary/)(Resources) | 从资源创建字典。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/cospdfdictionary/allkeys/) { get; } | 完整的键集合。包含可编辑和不可编辑的键。 |
| [Count](../../aspose.pdf.dataeditor/cospdfdictionary/count/) { get; } | 获取 `CosPdfDictionary` 中包含的元素数量。 |
| [IsReadOnly](../../aspose.pdf.dataeditor/cospdfdictionary/isreadonly/) { get; } | 获取指示 `CosPdfDictionary` 是否只读的值。 |
| [Item](../../aspose.pdf.dataeditor/cospdfdictionary/item/) { get; set; } | 获取或设置具有指定键的元素。 |
| [Keys](../../aspose.pdf.dataeditor/cospdfdictionary/keys/) { get; } | 可编辑键的集合。 |
| [Values](../../aspose.pdf.dataeditor/cospdfdictionary/values/) { get; } | 获取包含 `CosPdfDictionary` 中值的 ICollection。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary)(Document) | 创建一个将附加到文档的空字典。 |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary_1)(Page) | 创建一个将附加到页面的空字典。 |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | 将 [`ICosPdfPrimitive`](../icospdfprimitive/) 设置到字典中。 |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add_1)(string, ICosPdfPrimitive) | 将 [`ICosPdfPrimitive`](../icospdfprimitive/) 设置到字典中。 |
| [Clear](../../aspose.pdf.dataeditor/cospdfdictionary/clear/)() | 从 `CosPdfDictionary` 中移除所有项。 |
| [Contains](../../aspose.pdf.dataeditor/cospdfdictionary/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | 确定 `CosPdfDictionary` 是否包含特定值。 |
| [ContainsKey](../../aspose.pdf.dataeditor/cospdfdictionary/containskey/)(string) | 确定 `CosPdfDictionary` 是否包含具有指定键的元素。 |
| [CopyTo](../../aspose.pdf.dataeditor/cospdfdictionary/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/cospdfdictionary/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | 从 `CosPdfDictionary` 中移除特定对象的第一次出现。 |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove_1)(string) | 从 `CosPdfDictionary` 中移除具有指定键的元素。 |
| virtual [ToCosPdfBoolean](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfboolean/)() | 尝试将此实例转换为 [`CosPdfBoolean`](../cospdfboolean/)。 |
| override [ToCosPdfDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/tocospdfdictionary/)() | 尝试将此实例转换为 `CosPdfDictionary`。 |
| virtual [ToCosPdfName](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfname/)() | 尝试将此实例转换为 [`CosPdfName`](../cospdfname/)。 |
| virtual [ToCosPdfNumber](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfnumber/)() | 尝试将此实例转换为 [`CosPdfNumber`](../cospdfnumber/)。 |
| virtual [ToCosPdfString](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfstring/)() | 尝试将此实例转换为 [`CosPdfString`](../cospdfstring/)。 |
| [TryGetValue](../../aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/)(string, out ICosPdfPrimitive) | 用于访问字符串、名称、布尔值、数字等简单数据类型。对其他类型返回 null。 |

### 另请参见

* class [CosPdfPrimitive](../cospdfprimitive/)
* interface [ICosPdfPrimitive](../icospdfprimitive/)
* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)


