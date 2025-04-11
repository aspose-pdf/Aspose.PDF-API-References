---
title: Class TextElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Structure.TextElement 类。文档逻辑结构的一般文本元素
type: docs
weight: 10190
url: /zh/net/aspose.pdf.structure/textelement/
---
## TextElement class

文档逻辑结构的一般文本元素。

```csharp
public class TextElement : Element
```

## Properties

| Name | Description |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | （可选；PDF 1.4）作为结构元素及其子元素的确切替代文本。此替代文本（应适用于尽可能小的内容）在提取文档内容以支持残疾用户的可访问性或其他目的时非常有用。 |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | （可选）结构元素及其子元素的可读形式的替代描述，在提取文档内容以支持残疾用户的可访问性或其他目的时非常有用。 |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | 获取子元素集合。 |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | （可选；PDF 1.5）缩写的扩展形式。 |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | （可选；PDF 1.4）指定结构元素中所有文本的自然语言，除非被嵌套结构元素或标记内容的语言规范覆盖。 |
| [Text](../../aspose.pdf.structure/textelement/text/) { get; } | 获取文本结构元素的值。 |

## Methods

| Name | Description |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | 移除元素。 |

### See Also

* class [Element](../element/)
* namespace [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* assembly [Aspose.PDF](../../)