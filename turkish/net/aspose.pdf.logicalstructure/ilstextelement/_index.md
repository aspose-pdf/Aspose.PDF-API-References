---
title: ILSTextElement
second_title: Aspose.PDF for .NET API Referansı
description: Mantıksal yapıdaki satır içi düzey metin yapısı öğeleri için bir temel sınıfı temsil eder.
type: docs
weight: 4230
url: /tr/net/aspose.pdf.logicalstructure/ilstextelement/
---
## ILSTextElement class

Mantıksal yapıdaki satır içi düzey metin yapısı öğeleri için bir temel sınıfı temsil eder.

```csharp
public abstract class ILSTextElement : ILSElement, ITextElement
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ActualText](../../aspose.pdf.logicalstructure/structureelement/actualtext) { get; set; } | Yapı öğesi için gerçek metni alır veya ayarlar. |
| [AlternativeText](../../aspose.pdf.logicalstructure/structureelement/alternativetext) { get; set; } | Yapı öğesi için alternatif metni alır veya ayarlar. |
| [Attributes](../../aspose.pdf.logicalstructure/structureelement/attributes) { get; } | AlırStructureAttributeCollection nesne. |
| [ChildElements](../../aspose.pdf.logicalstructure/element/childelements) { get; } | Alt öğelerin koleksiyonunu alırElement nesneler. |
| [DefaultAttributeOwner](../../aspose.pdf.logicalstructure/structureelement/defaultattributeowner) { get; } | AlırAttributeOwnerStandard nesne. |
| [ExpansionText](../../aspose.pdf.logicalstructure/structureelement/expansiontext) { get; set; } | Yapı öğesi için genişletme metnini alır veya ayarlar. |
| [ID](../../aspose.pdf.logicalstructure/structureelement/id) { get; } | Yapı elemanının kimliğini alır. |
| [Language](../../aspose.pdf.logicalstructure/structureelement/language) { get; set; } | Yapı elemanının dilini alır veya ayarlar. |
| [ParentElement](../../aspose.pdf.logicalstructure/element/parentelement) { get; } | Üst öğeyi alın. |
| [StructureTextState](../../aspose.pdf.logicalstructure/ilstextelement/structuretextstate) { get; } | AlırStructureTextState geçerli öğe için nesne. |
| [StructureType](../../aspose.pdf.logicalstructure/structureelement/structuretype) { get; } | Yapı elemanının türünü alır. |
| [Title](../../aspose.pdf.logicalstructure/structureelement/title) { get; set; } | Yapı elemanının başlığını alır veya ayarlar. |

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
| [SetText](../../aspose.pdf.logicalstructure/ilstextelement/settext)(string) | Metin içeriğini mevcut metin öğesine ekler. |
| override [ToString](../../aspose.pdf.logicalstructure/structureelement/tostring)() | Geçerli nesneyi temsil eden bir dize döndürür. |

### Ayrıca bakınız

* class [ILSElement](../ilselement)
* interface [ITextElement](../itextelement)
* ad alanı [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->