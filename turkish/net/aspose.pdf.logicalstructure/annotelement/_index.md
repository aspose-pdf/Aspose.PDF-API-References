---
title: Class AnnotElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.AnnotElement sınıfı. Mantıksal yapıdaki Annot yapı elemanını temsil eder
type: docs
weight: 6180
url: /tr/net/aspose.pdf.logicalstructure/annotelement/
---
## AnnotElement sınıfı

Mantıksal yapıdaki Annot yapı elemanını temsil eder.

```csharp
public sealed class AnnotElement : AnnotationElement
```

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Yapı elemanı için gerçek metni alır veya ayarlar. |
| [AlternateDescriptions](../../aspose.pdf.logicalstructure/annotationelement/alternatedescriptions/) { get; set; } | Not için Alternatif Açıklamaları alır veya ayarlar. Not için görüntülenecek metin veya bu tür bir not metin göstermiyorsa, notun içeriğinin insan tarafından okunabilir formda alternatif açıklaması. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Yapı elemanı için alternatif metni alır veya ayarlar. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | StructureAttributeCollection nesnesini alır. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Element nesnelerinin çocuk koleksiyonunu alır. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | AttributeOwnerStandard nesnesini alır. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Yapı elemanı için genişletme metnini alır veya ayarlar. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Yapı elemanı için ID'yi alır. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Yapı elemanı için dili alır veya ayarlar. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Bazı veya tüm çocuk elemanların render edileceği sayfayı alır. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Üst elemanı alır. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Yapı elemanının türünü alır. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Yapı elemanı için başlığı alır veya ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Elementi çocuklar koleksiyonuna ekler. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Mevcut yapı elemanının üst elemanını değiştirir. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Tüm çocukları temizler. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Yapı elemanı için ID'yi temizler. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Belirtilen türdeki Elemanları bulur. |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Yapı elemanı için ID oluşturur. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Belirtilen indekste çocuklar koleksiyonuna Element ekler. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Yapıdan bir elemanı, ona ait referansı üst nesneden, ona ait referansları çocuk nesnelerden ve belgede ilgili nesneyi kaldırır. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Yapıdan bir elemanı, ona ait referansı üst nesneden, ona ait referansları çocuk nesnelerden ve belgede ilgili nesneyi kaldırır. Kaldırılan nesnenin çocuk nesnelerini, kaldırılan nesnenin eski üst çocuk nesneler koleksiyonuna ekler. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Çocuğu kaldırır. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Yapı elemanı için ID'yi ayarlar. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Yapı elemanı için özel etiketi ayarlar. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Bir yapı elemanını Annotation ile bağlar. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Bir yapı elemanını Artifact ile bağlar. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Bir yapı elemanını içerik akışı BDC operatörü ile bağlar. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Bir yapı elemanını içerik akışı XForm ile bağlar. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Bir yapı elemanını XImage ile bağlar. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Mevcut nesneyi temsil eden bir dize döndürür. |

### Ayrıca Bakınız

* sınıf [AnnotationElement](../annotationelement/)
* ad alanı [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* derleme [Aspose.PDF](../../)