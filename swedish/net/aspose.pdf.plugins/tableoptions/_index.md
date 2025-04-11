---
title: Class TableOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TableOptions klass. Representerar alternativ för att lägga till tabell i dokumentet via TableGenerator-plugin
type: docs
weight: 9360
url: /sv/net/aspose.pdf.plugins/tableoptions/
---
## TableOptions klass

Representerar alternativ för att lägga till tabell i dokumentet via [`TableGenerator`](../tablegenerator/) plugin.

```csharp
public sealed class TableOptions : PdfGeneratorOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TableOptions](tableoptions/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Inputs](../../aspose.pdf.plugins/pdfgeneratoroptions/inputs/) { get; } | Returnerar PdfGenerator plugin datainsamling. |
| [Outputs](../../aspose.pdf.plugins/pdfgeneratoroptions/outputs/) { get; } | Hämtar samling av tillagda mål för att spara operationens resultat. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Create](../../aspose.pdf.plugins/tableoptions/create/)() | Skapar en instans av `TableOptions`. |
| [AddInput](../../aspose.pdf.plugins/pdfgeneratoroptions/addinput/)(IDataSource) | Lägger till ny datakälla till PdfGenerator plugin datainsamling. |
| [AddOutput](../../aspose.pdf.plugins/pdfgeneratoroptions/addoutput/)(IDataSource) | Lägger till ny datakälla till PdfGenerator plugin datainsamling. |
| [AddTable](../../aspose.pdf.plugins/tableoptions/addtable/)() | Lägger till tabell i dokumentet. |
| [InsertPageAfter](../../aspose.pdf.plugins/tableoptions/insertpageafter/)(int) | Infogar sida efter angiven sida. |
| [InsertPageBefore](../../aspose.pdf.plugins/tableoptions/insertpagebefore/)(int) | Infogar sida före angiven sida. |

### Se Även

* klass [PdfGeneratorOptions](../pdfgeneratoroptions/)
* namnrymd [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)