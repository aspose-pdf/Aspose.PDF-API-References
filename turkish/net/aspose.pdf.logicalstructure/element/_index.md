---
title: Class Element
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.Element sınıfı. Mantıksal yapıda bir öğe için temel sınıfı temsil eder
type: docs
weight: 6320
url: /tr/net/aspose.pdf.logicalstructure/element/
---
## Element sınıfı

Mantıksal yapıda bir öğe için temel sınıfı temsil eder.

```csharp
public abstract class Element
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Element nesnelerinin çocuk koleksiyonunu alır. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Üst öğeyi alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Element'i çocuklar koleksiyonuna ekler. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Tüm çocukları temizler. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Verilen türdeki Öğeleri bulur |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Belirtilen indekste çocuklar koleksiyonuna Element ekler. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Belirtilen indekste çocuğu kaldırır. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_2)(Annotation) | Bir yapı öğesini Annotation'a bağlar. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag)(Artifact) | Bir yapı öğesini Artifact'a bağlar. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_1)(BDC) | Bir yapı öğesini içerik akışı BDC operatörüne bağlar. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_3)(XForm) | Bir yapı öğesini içerik akışı XForm'a bağlar. |
| abstract [Tag](../../aspose.pdf.logicalstructure/element/tag/#tag_4)(XImage) | Bir yapı öğesini XImage'a bağlar. |
| override [ToString](../../aspose.pdf.logicalstructure/element/tostring/)() | Mevcut nesneyi temsil eden bir dize döndürür. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)