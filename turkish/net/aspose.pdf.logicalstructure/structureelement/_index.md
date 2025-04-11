---
title: Class StructureElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.StructureElement sınıfı. Mantıksal yapıdaki yapı öğeleri için bir temel sınıfı temsil eder.
type: docs
weight: 6700
url: /tr/net/aspose.pdf.logicalstructure/structureelement/
---
## StructureElement sınıfı

Mantıksal yapıdaki yapı öğeleri için bir temel sınıfı temsil eder.

```csharp
public abstract class StructureElement : Element
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Yapı öğesi için gerçek metni alır veya ayarlar. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Yapı öğesi için alternatif metni alır veya ayarlar. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | StructureAttributeCollection nesnesini alır. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Element nesnelerinin çocuk koleksiyonunu alır. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | AttributeOwnerStandard nesnesini alır. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Yapı öğesi için genişletme metnini alır veya ayarlar. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Yapı öğesi için ID'yi alır. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Yapı öğesi için dili alır veya ayarlar. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Bazı veya tüm çocuk öğelerin render edileceği sayfayı alır. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Üst öğeyi alır. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Yapı öğesinin türünü alır. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Yapı öğesi için başlığı alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Element'i çocuklar koleksiyonuna ekler. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Mevcut yapı öğesi için üst öğeyi değiştirir. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Tüm çocukları temizler. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Yapı öğesi için ID'yi temizler. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Verilen türdeki öğeleri bulur. |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Yapı öğesi için ID oluşturur. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Belirtilen indeksde çocuklar koleksiyonuna Element ekler. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Bir öğeyi yapıdan, ona referansı üst nesneden, ona referansları çocuk nesnelerden, ilgili nesneyi belgede kaldırır. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Bir öğeyi yapıdan, ona referansı üst nesneden, ona referansları çocuk nesnelerden ve ilgili nesneyi belgede kaldırır. Kaldırılan nesnenin çocuk nesnelerini, kaldırılan nesnenin eski üst çocuk nesne koleksiyonuna ekler. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Çocuğu kaldırır. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Yapı öğesi için ID'yi ayarlar. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Yapı öğesi için özel etiketi ayarlar. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/#tag_2)(Annotation) | Bir yapı öğesini Annotation'a bağlar. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/#tag)(Artifact) | Bir yapı öğesini Artifact'a bağlar. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/#tag_1)(BDC) | Bir yapı öğesini içerik akışı BDC operatörüne bağlar. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/#tag_3)(XForm) | Bir yapı öğesini içerik akışı XForm'a bağlar. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/#tag_4)(XImage) | Bir yapı öğesini XImage'a bağlar. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Mevcut nesneyi temsil eden bir dize döndürür. |

### Ayrıca Bakınız

* sınıf [Element](../element/)
* ad alanı [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* derleme [Aspose.PDF](../../)