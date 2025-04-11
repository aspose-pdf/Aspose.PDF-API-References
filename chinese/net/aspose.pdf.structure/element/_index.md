---
title: Class Element
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Structure.Element 类。表示逻辑结构的基本元素
type: docs
weight: 10140
url: /zh/net/aspose.pdf.structure/element/
---
## 元素类

表示逻辑结构的基本元素。

```csharp
public abstract class Element
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | （可选；PDF 1.4）作为结构元素及其子元素的确切替代文本。此替代文本（应尽可能适用于较小的内容片段）在提取文档内容以支持残疾用户的可访问性或其他目的时非常有用。 |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | （可选）结构元素及其子元素的替代描述，以人类可读的形式表示，在提取文档内容以支持残疾用户的可访问性或其他目的时非常有用。 |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | 获取子元素集合。 |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | （可选；PDF 1.5）缩写的扩展形式。 |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | （可选；PDF 1.4）指定结构元素中所有文本的自然语言，除非被嵌套结构元素或标记内容的语言规范覆盖。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | 移除元素。 |

### 另请参阅

* 命名空间 [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* 程序集 [Aspose.PDF](../../)