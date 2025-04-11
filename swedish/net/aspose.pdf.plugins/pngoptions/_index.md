---
title: Class PngOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PngOptions klass. Representerar Pdf till Png-konverteringsalternativ för Png-plugin
type: docs
weight: 9180
url: /sv/net/aspose.pdf.plugins/pngoptions/
---
## PngOptions klass

Representerar Pdf till Png-konverteringsalternativ för [`Png`](../png/) plugin.

```csharp
public sealed class PngOptions : PdfToImageOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PngOptions](pngoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Hämtar bildkonverteringsläge. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Returnerar [`PdfToImage`](../pdftoimage/) plugin-datainsamling. |
| override [OperationName](../../aspose.pdf.plugins/pngoptions/operationname/) { get; } | Returnerar namnet på operationen. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Hämtar eller ställer in upplösningsvärdet för de resulterande bilderna. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Hämtar eller ställer in en lista över sidor för processen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Lägger till ny datakälla till [`PdfToImage`](../pdftoimage/) plugin-datainsamling. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Ställer in ny sparad datakälla. Kan endast vara en. Om du vill spara bilder i minnesströmmar, skicka null som parameter. |

### Se Även

* klass [PdfToImageOptions](../pdftoimageoptions/)
* namnrymd [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* sammansättning [Aspose.PDF](../../)