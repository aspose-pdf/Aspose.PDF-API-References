---
title: Class TableTHElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.TableTHElement sınıfı. Tablo mantıksal yapısındaki TH yapı elemanını temsil eder
type: docs
weight: 6830
url: /tr/net/aspose.pdf.logicalstructure/tablethelement/
---
## TableTHElement sınıfı

Tablo mantıksal yapısındaki TH yapı elemanını temsil eder.

```csharp
public sealed class TableTHElement : TableCellElement
```

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext/) { get; set; } | Yapı elemanı için gerçek metni alır veya ayarlar. |
| [Alignment](../../aspose.pdf.logicalstructure/tablecellelement/alignment/) { get; set; } | Hücre hizalamasını alır veya ayarlar. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext/) { get; set; } | Yapı elemanı için alternatif metni alır veya ayarlar. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes/) { get; } | StructureAttributeCollection nesnesini alır. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tablecellelement/backgroundcolor/) { get; set; } | Hücre arka plan rengini alır veya ayarlar. |
| [Border](../../aspose.pdf.logicalstructure/tablecellelement/border/) { get; set; } | Hücre kenarlığını alır veya ayarlar. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements/) { get; } | Element nesnelerinin çocuk koleksiyonunu alır. |
| [ColSpan](../../aspose.pdf.logicalstructure/tablecellelement/colspan/) { get; set; } | Sütun aralığını alır veya ayarlar. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner/) { get; } | AttributeOwnerStandard nesnesini alır. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tablecellelement/defaultcelltextstate/) { get; set; } | Varsayılan hücre metin durumunu alır veya ayarlar. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext/) { get; set; } | Yapı elemanı için genişletme metnini alır veya ayarlar. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id/) { get; } | Yapı elemanı için ID'yi alır. |
| [IsNoBorder](../../aspose.pdf.logicalstructure/tablecellelement/isnoborder/) { get; set; } | Hücrenin kenarlığının olup olmadığını alır veya ayarlar. |
| [IsWordWrapped](../../aspose.pdf.logicalstructure/tablecellelement/iswordwrapped/) { get; set; } | Hücrenin metninin kelime sarılıp sarılmadığını alır veya ayarlar. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language/) { get; set; } | Yapı elemanı için dili alır veya ayarlar. |
| [Margin](../../aspose.pdf.logicalstructure/tablecellelement/margin/) { get; set; } | İç boşluğu alır veya ayarlar. |
| [Page](../../aspose.pdf.logicalstructure/structureelement/page/) { get; } | Bazı veya tüm çocuk elemanların render edileceği sayfayı alır. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement/) { get; } | Üst elemanı alır. |
| [RowSpan](../../aspose.pdf.logicalstructure/tablecellelement/rowspan/) { get; set; } | Satır aralığını alır veya ayarlar. |
| [StructureTextState](../../aspose.pdf.logicalstructure/tablecellelement/structuretextstate/) { get; } | Mevcut eleman için StructureTextState nesnesini alır. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype/) { get; } | Yapı elemanının türünü alır. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title/) { get; set; } | Yapı elemanı için başlığı alır veya ayarlar. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tablecellelement/verticalalignment/) { get; set; } | Dikey hizalamayı alır veya ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [AdjustPosition](../../aspose.pdf.logicalstructure/tablecellelement/adjustposition/)(PositionSettings) |  |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild/)(Element, bool) | Elementi çocuklar koleksiyonuna ekler. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement/)(StructureElement, bool) | Mevcut yapı elemanı için üst elemanı değiştirir. |
| [ClearChilds](../../aspose.pdf.logicalstructure/element/clearchilds/)() | Tüm çocukları temizler. |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid/)() | Yapı elemanı için ID'yi temizler. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements/)(bool) | Verilen türdeki Elemanları bulur. |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid/)() | Yapı elemanı için ID oluşturur. |
| [InsertChild](../../aspose.pdf.logicalstructure/element/insertchild/)(Element, int, bool) | Belirtilen indekste çocuklar koleksiyonuna Element ekler. |
| [Remove](../../aspose.pdf.logicalstructure/structureelement/remove/)() | Yapıdan bir elemanı, ona ait referansı üst nesneden, ona ait referansları çocuk nesnelerden ve belgede karşılık gelen nesneyi kaldırır. |
| [RemoveAndMoveItsChildObjectsToItsParent](../../aspose.pdf.logicalstructure/structureelement/removeandmoveitschildobjectstoitsparent/)(bool) | Yapıdan bir elemanı, ona ait referansı üst nesneden, ona ait referansları çocuk nesnelerden ve belgede karşılık gelen nesneyi kaldırır. Kaldırılan nesnenin çocuk nesnelerini, kaldırılan nesnenin eski üst çocuk nesneler koleksiyonuna ekler. |
| [RemoveChild](../../aspose.pdf.logicalstructure/element/removechild/)(int) | Belirtilen indekste çocuğu kaldırır. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid/)(string) | Yapı elemanı için ID'yi ayarlar. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag/)(string) | Yapı elemanı için özel etiketi ayarlar. |
| [SetText](../../aspose.pdf.logicalstructure/tablecellelement/settext/)(string) |  |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Annotation) | Bir yapı elemanını Annotation'a bağlar. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(Artifact) | Bir yapı elemanını Artifact'a bağlar. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(BDC) | Bir yapı elemanını içerik akışı BDC operatörüne bağlar. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XForm) | Bir yapı elemanını içerik akışı XForm'a bağlar. |
| override [Tag](../../aspose.pdf.logicalstructure/structureelement/tag/)(XImage) | Bir yapı elemanını XImage'a bağlar. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring/)() | Mevcut nesneyi temsil eden bir dize döndürür. |

### Ayrıca Bakınız

* sınıf [TableCellElement](../tablecellelement/)
* ad alanı [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* derleme [Aspose.PDF](../../)