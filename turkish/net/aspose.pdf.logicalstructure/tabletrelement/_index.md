---
title: TableTRElement
second_title: Aspose.PDF for .NET API Referansı
description: Tablonun mantıksal yapısında TR yapı öğesini temsil eder.
type: docs
weight: 4680
url: /tr/net/aspose.pdf.logicalstructure/tabletrelement/
---
## TableTRElement class

Tablonun mantıksal yapısında TR yapı öğesini temsil eder.

```csharp
public sealed class TableTRElement : TableChildElement
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext) { get; set; } | Yapı öğesi için gerçek metni alır veya ayarlar. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext) { get; set; } | Yapı öğesi için alternatif metni alır veya ayarlar. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes) { get; } | AlırStructureAttributeCollection nesne. |
| [BackgroundColor](../../aspose.pdf.logicalstructure/tabletrelement/backgroundcolor) { get; set; } | Satır arka plan rengini alır veya ayarlar. |
| [Border](../../aspose.pdf.logicalstructure/tabletrelement/border) { get; set; } | Satır kenarlığını alır veya ayarlar. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements) { get; } | Alt öğelerin koleksiyonunu alırElement nesneler. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner) { get; } | AlırAttributeOwnerStandard nesne. |
| [DefaultCellBorder](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellborder) { get; set; } | Varsayılan hücre kenarlığını alır. |
| [DefaultCellPadding](../../aspose.pdf.logicalstructure/tabletrelement/defaultcellpadding) { get; set; } | Satır hücreleri için varsayılan kenar boşluğunu alır veya ayarlar. |
| [DefaultCellTextState](../../aspose.pdf.logicalstructure/tabletrelement/defaultcelltextstate) { get; set; } | Satır hücreleri için varsayılan metin durumunu alır veya ayarlar |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext) { get; set; } | Yapı öğesi için genişletme metnini alır veya ayarlar. |
| [FixedRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/fixedrowheight) { get; set; } | Sabit satır yüksekliğini alır - satırın sabit yüksekliği olabilir. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id) { get; } | Yapı elemanının kimliğini alır. |
| [IsInNewPage](../../aspose.pdf.logicalstructure/tabletrelement/isinnewpage) { get; set; } | Yeni sayfada satır düzeltildi - bu özelliğe sahip sayfa sonraki sayfaya yazdırılmalıdır Varsayılan false. |
| [IsRowBroken](../../aspose.pdf.logicalstructure/tabletrelement/isrowbroken) { get; set; } | Satırın iki sayfa arasında bölünebileceğini alır. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language) { get; set; } | Yapı elemanının dilini alır veya ayarlar. |
| [MinRowHeight](../../aspose.pdf.logicalstructure/tabletrelement/minrowheight) { get; set; } | Satır için yükseklik alır. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement) { get; } | Üst öğeyi alın. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype) { get; } | Yapı elemanının türünü alır. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title) { get; set; } | Yapı elemanının başlığını alır veya ayarlar. |
| [VerticalAlignment](../../aspose.pdf.logicalstructure/tabletrelement/verticalalignment) { get; set; } | Dikey hizalamayı alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AppendChild](../../aspose.pdf.logicalstructure/element/appendchild)(Element) | EkleElement çocuk koleksiyonuna. |
| [ChangeParentElement](../../aspose.pdf.logicalstructure/structureelement/changeparentelement)(StructureElement) | Geçerli yapı için üst öğeyi değiştir element |
| [ClearId](../../aspose.pdf.logicalstructure/structureelement/clearid)() | Yapı öğesi için kimliği temizle. |
| [CreateTD](../../aspose.pdf.logicalstructure/tabletrelement/createtd)() | Oluşturur[`TableTHElement`](../tablethelement) ve mevcut tabloya ekledi. |
| [CreateTH](../../aspose.pdf.logicalstructure/tabletrelement/createth)() | Oluşturur[`TableTHElement`](../tablethelement) ve mevcut tabloya ekledi. |
| [FindElements&lt;T&gt;](../../aspose.pdf.logicalstructure/element/findelements)(bool) | Belirli bir türdeki Öğeleri Bul |
| [GenerateId](../../aspose.pdf.logicalstructure/structureelement/generateid)() | Yapı öğesi için kimlik oluşturun. |
| [SetId](../../aspose.pdf.logicalstructure/structureelement/setid)(string) | Yapı öğesi için kimliği ayarlar. |
| [SetTag](../../aspose.pdf.logicalstructure/structureelement/settag)(string) | Yapı öğesi için özel etiket ayarlar. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |

### Ayrıca bakınız

* class [TableChildElement](../tablechildelement)
* ad alanı [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
