---
title: TableElement
second_title: Aspose.PDF for .NET API Referansı
description: Mantıksal yapıdaki Tablo yapı öğesini temsil eder.
type: docs
weight: 4610
url: /tr/net/aspose.pdf.logicalstructure/tableelement/
---
## TableElement class

Mantıksal yapıdaki Tablo yapı öğesini temsil eder.

```csharp
public sealed class TableElement : BLSElement
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext) { get; set; } | Yapı öğesi için gerçek metni alır veya ayarlar. |
| [Alignment](../../aspose.pdf.logicalstructure/tableelement/alignment) { get; set; } | Tablo hizalamasını alır veya ayarlar. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext) { get; set; } | Yapı öğesi için alternatif metni alır veya ayarlar. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes) { get; } | AlırStructureAttributeCollection nesne. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tableelement/backgroundcolor) { get; set; } | Tablo arka plan rengini alır veya ayarlar. |
| [Border](../../aspose.pdf.logicalstructure/tableelement/border) { get; set; } | Tablo kenarlığını alır veya ayarlar. |
| [Broken](../../aspose.pdf.logicalstructure/tableelement/broken) { get; set; } | Tablo dikeyini bozuk alır veya ayarlar; |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements) { get; } | Alt öğelerin koleksiyonunu alırElement nesneler. |
| [ColumnAdjustment](../../aspose.pdf.logicalstructure/tableelement/columnadjustment) { get; set; } | Tablo sütunu ayarını alır veya ayarlar. |
| [ColumnWidths](../../aspose.pdf.logicalstructure/tableelement/columnwidths) { get; set; } | Tablonun sütun genişliklerini alır. |
| [CornerStyle](../../aspose.pdf.logicalstructure/tableelement/cornerstyle) { get; set; } | Kenarlık köşelerinin stillerini alır veya ayarlar |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner) { get; } | AlırAttributeOwnerStandard nesne. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tableelement/defaultcellborder) { get; set; } | Varsayılan hücre kenarlığını alır. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tableelement/defaultcellpadding) { get; set; } | Varsayılan hücre dolgusunu alır veya ayarlar. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tableelement/defaultcelltextstate) { get; set; } | Varsayılan hücre metni durumunu alır veya ayarlar. |
| [DefaultColumnWidth](../../aspose.pdf.logicalstructure/tableelement/defaultcolumnwidth) { get; set; } | Varsayılan sütun genişliğini alır veya ayarlar. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext) { get; set; } | Yapı öğesi için genişletme metnini alır veya ayarlar. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id) { get; } | Yapı elemanının kimliğini alır. |
| [IsBordersIncluded](../../aspose.pdf.logicalstructure/tableelement/isbordersincluded) { get; set; } | Sütun genişliklerinde bulunan kenarlığı alır veya ayarlar. |
| [IsBroken](../../aspose.pdf.logicalstructure/tableelement/isbroken) { get; set; } | Tablonun bozuk olduğunu alır veya ayarlar - sonraki sayfa için kesilecektir. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language) { get; set; } | Yapı elemanının dilini alır veya ayarlar. |
| [Left](../../aspose.pdf.logicalstructure/tableelement/left) { get; set; } | Tablonun sol koordinatını alır veya ayarlar. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement) { get; } | Üst öğeyi alın. |
| [RepeatingColumnsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingcolumnscount) { get; set; } | Tablo için maksimum sütun sayısını alır veya ayarlar. |
| [RepeatingRowsCount](../../aspose.pdf.logicalstructure/tableelement/repeatingrowscount) { get; set; } | Birkaç sayfa için tekrarlanan ilk satır sayısını alır. |
| [RepeatingRowsStyle](../../aspose.pdf.logicalstructure/tableelement/repeatingrowsstyle) { get; set; } | Yinelenen satırlar için stili alır. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype) { get; } | Yapı elemanının türünü alır. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title) { get; set; } | Yapı elemanının başlığını alır veya ayarlar. |
| [Top](../../aspose.pdf.logicalstructure/tableelement/top) { get; set; } | Masa üstü koordinatını alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild)(Element) | EkleElement çocuk koleksiyonuna. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement)(StructureElement) | Geçerli yapı için üst öğeyi değiştir element |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid)() | Yapı öğesi için kimliği temizle. |
| [CreateTBody](../../aspose.pdf.logicalstructure/tableelement/createtbody)() | Oluşturur[`TableTHeadElement`](../tabletheadelement) ve mevcut tabloya ekledi. |
| [CreateTFoot](../../aspose.pdf.logicalstructure/tableelement/createtfoot)() | Oluşturur[`TableTFootElement`](../tabletfootelement) ve mevcut tabloya ekledi. |
| [CreateTHead](../../aspose.pdf.logicalstructure/tableelement/createthead)() | Oluşturur[`TableTHeadElement`](../tabletheadelement) ve mevcut tabloya ekledi. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements)(bool) | Belirli bir türdeki Öğeleri Bul |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid)() | Yapı öğesi için kimlik oluşturun. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid)(string) | Yapı öğesi için kimliği ayarlar. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag)(string) | Yapı öğesi için özel etiket ayarlar. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |

### Ayrıca bakınız

* class [BLSElement](../blselement)
* ad alanı [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
