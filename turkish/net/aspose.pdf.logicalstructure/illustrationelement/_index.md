---
title: Class IllustrationElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.IllustrationElement sınıfı. Mantıksal yapıdaki illüstrasyon yapı öğeleri için bir temel sınıfı temsil eder
type: docs
weight: 6420
url: /tr/net/aspose.pdf.logicalstructure/illustrationelement/
---
## IllustrationElement sınıfı

Mantıksal yapıdaki illüstrasyon yapı öğeleri için bir temel sınıfı temsil eder.

```csharp
public abstract class IllustrationElement : StructureElement, IAdjustPosition
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
| [AdjustPosition](../../aspose.pdf.logicalstructure/illustrationelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Element'i çocuklar koleksiyonuna ekler. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Mevcut yapı öğesi için üst öğeyi değiştirir |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Tüm çocukları temizler. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Yapı öğesi için ID'yi temizler. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Belirtilen türdeki öğeleri bulur |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Yapı öğesi için ID oluşturur. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Belirtilen indekste çocuklar koleksiyonuna Element ekler. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Bir öğeyi yapıdan, ona ait referansı üst nesneden, ona ait referansları çocuk nesnelerden ve belgede karşılık gelen nesneyi kaldırır. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Bir öğeyi yapıdan, ona ait referansı üst nesneden, ona ait referansları çocuk nesnelerden ve belgede karşılık gelen nesneyi kaldırır. Kaldırılan nesnenin çocuk nesnelerini, kaldırılan nesnenin eski üst çocuk nesneler koleksiyonuna ekler. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Çocuğu kaldırır. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Yapı öğesi için ID'yi ayarlar. |
| virtual [SetImage](../../aspose.pdf.logicalstructure/illustrationelement/setimage/#setimage)(string, double) | Mevcut illüstrasyon öğesine resim ekler. |
| virtual [SetImage](../../aspose.pdf.logicalstructure/illustrationelement/setimage/#setimage_1)(string, double, double) | Mevcut illüstrasyon öğesine resim ekler. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Yapı öğesi için özel etiketi ayarlar. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Bir yapı öğesini Annotation ile bağlar. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Bir yapı öğesini Artifact ile bağlar. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Bir yapı öğesini içerik akışı BDC operatörü ile bağlar. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Bir yapı öğesini içerik akışı XForm ile bağlar. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Bir yapı öğesini XImage ile bağlar. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Mevcut nesneyi temsil eden bir dize döndürür. |

### Ayrıca Bakınız

* sınıf [StructureElement](../structureelement/)
* arayüz [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* ad alanı [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* derleme [Aspose.PDF](../../)