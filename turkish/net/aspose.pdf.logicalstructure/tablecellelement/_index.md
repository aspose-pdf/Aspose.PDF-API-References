---
title: TableCellElement
second_title: Aspose.PDF for .NET API Referansı
description: Mantıksal yapıdaki tablo hücresi öğeleri TH ve TD için bir temel sınıfı temsil eder.
type: docs
weight: 4590
url: /tr/net/aspose.pdf.logicalstructure/tablecellelement/
---
## TableCellElement class

Mantıksal yapıdaki tablo hücresi öğeleri (TH ve TD) için bir temel sınıfı temsil eder.

```csharp
public abstract class TableCellElement : TableChildElement, ITextElement
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext) { get; set; } | Yapı öğesi için gerçek metni alır veya ayarlar. |
| [Alignment](../../aspose.pdf.logicalstructure/tablecellelement/alignment) { get; set; } | Hücre hizalamasını alır veya ayarlar. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext) { get; set; } | Yapı öğesi için alternatif metni alır veya ayarlar. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes) { get; } | AlırStructureAttributeCollection nesne. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tablecellelement/backgroundcolor) { get; set; } | Hücre arka plan rengini alır veya ayarlar. |
| [Border](../../aspose.pdf.logicalstructure/tablecellelement/border) { get; set; } | Hücre kenarlığını alır veya ayarlar. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements) { get; } | Alt öğelerin koleksiyonunu alırElement nesneler. |
| [ColSpan](../../aspose.pdf.logicalstructure/tablecellelement/colspan) { get; set; } | Sütun aralığını alır veya ayarlar. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner) { get; } | AlırAttributeOwnerStandard nesne. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tablecellelement/defaultcelltextstate) { get; set; } | Varsayılan hücre metni durumunu alır veya ayarlar. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext) { get; set; } | Yapı öğesi için genişletme metnini alır veya ayarlar. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id) { get; } | Yapı elemanının kimliğini alır. |
| [IsNoBorder](../../aspose.pdf.logicalstructure/tablecellelement/isnoborder) { get; set; } | Hücrenin kenarlığı olduğunu alır veya ayarlar. |
| [IsWordWrapped](../../aspose.pdf.logicalstructure/tablecellelement/iswordwrapped) { get; set; } | Hücrenin sarılmış metin sözcüğünü alır veya ayarlar. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language) { get; set; } | Yapı elemanının dilini alır veya ayarlar. |
| [Margin](../../aspose.pdf.logicalstructure/tablecellelement/margin) { get; set; } | Dolguyu alır veya ayarlar. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement) { get; } | Üst öğeyi alın. |
| [RowSpan](../../aspose.pdf.logicalstructure/tablecellelement/rowspan) { get; set; } | Satır aralığını alır veya ayarlar. |
| [StructureTextState](../../aspose.pdf.logicalstructure/tablecellelement/structuretextstate) { get; } | AlırStructureTextState geçerli öğe için nesne. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype) { get; } | Yapı elemanının türünü alır. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title) { get; set; } | Yapı elemanının başlığını alır veya ayarlar. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tablecellelement/verticalalignment) { get; set; } | Dikey hizalamayı alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild)(Element) | EkleElement çocuk koleksiyonuna. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement)(StructureElement) | Geçerli yapı için üst öğeyi değiştir element |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid)() | Yapı öğesi için kimliği temizle. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements)(bool) | Belirli bir türdeki Öğeleri Bul |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid)() | Yapı öğesi için kimlik oluşturun. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid)(string) | Yapı öğesi için kimliği ayarlar. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag)(string) | Yapı öğesi için özel etiket ayarlar. |
| [SetText](../../aspose.pdf.logicalstructure/tablecellelement/settext)(string) | Metin içeriğini mevcut metin öğesine ekler. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |

### Ayrıca bakınız

* class [TableChildElement](../tablechildelement)
* interface [ITextElement](../itextelement)
* ad alanı [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
