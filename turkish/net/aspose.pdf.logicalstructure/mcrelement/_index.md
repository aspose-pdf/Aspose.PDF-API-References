---
title: Class MCRElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.MCRElement sınıfı. Mantıksal yapıda işaretli içerik referans nesnesini temsil eder
type: docs
weight: 6500
url: /tr/net/aspose.pdf.logicalstructure/mcrelement/
---
## MCRElement sınıfı

Mantıksal yapıda işaretli içerik referans nesnesini temsil eder.

```csharp
public sealed class MCRElement : Element
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Element nesnelerinin çocuk koleksiyonunu alır. |
| [MCID](../../aspose.pdf.logicalstructure/mcrelement/mcid/) { get; } | İşaretli içerik referans nesnesinin MCID'sini alır. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Üst elementi alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Element'i çocuklar koleksiyonuna ekler. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Tüm çocukları temizler. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Verilen türdeki Elementleri bulur |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Belirtilen indekste çocuklar koleksiyonuna Element ekler. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Belirtilen indekste çocuğu kaldırır. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_2)(Annotation) | Bir yapı elemanını Annotation'a bağlar. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag)(Artifact) | Bir yapı elemanını Artifact'a bağlar. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_1)(BDC) | Bir yapı elemanını içerik akışı BDC operatörüne bağlar. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_3)(XForm) | Bir yapı elemanını içerik akışı XForm'a bağlar. |
| override [Tag](../../aspose.pdf.logicalstructure/mcrelement/tag/#tag_4)(XImage) | Bir yapı elemanını XImage'a bağlar. |
| override [ToString](../../aspose.pdf.logicalstructure/mcrelement/tostring/)() | Mevcut nesneyi temsil eden bir dize döndürür. |

### Ayrıca Bakınız

* sınıf [Element](../element/)
* ad alanı [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* derleme [Aspose.PDF](../../)