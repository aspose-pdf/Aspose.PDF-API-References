---
title: Class JpegOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.JpegOptions klass. Representerar Pdf till Jpeg konverteringsalternativ för Jpeg-plugin
type: docs
weight: 8920
url: /sv/net/aspose.pdf.plugins/jpegoptions/
---
## JpegOptions klass

Representerar Pdf till Jpeg konverteringsalternativ för [`Jpeg`](../jpeg/) plugin.

```csharp
public sealed class JpegOptions : PdfToImageOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [JpegOptions](jpegoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Hämtar bildkonverteringsläge. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Returnerar [`PdfToImage`](../pdftoimage/) plugin datainsamling. |
| override [OperationName](../../aspose.pdf.plugins/jpegoptions/operationname/) { get; } | Returnerar namnet på operationen. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Hämtar eller ställer in upplösningsvärdet för de resulterande bilderna. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Hämtar eller ställer in en lista över sidor för processen. |
| [Quality](../../aspose.pdf.plugins/jpegoptions/quality/) { get; set; } | Hämtar och ställer in Jpeg-kvalitet |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Lägger till ny datakälla till [`PdfToImage`](../pdftoimage/) plugin datainsamling. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Ställer in ny spara datakälla. Kan endast vara en . Om du vill spara bilder i minnesströmmar, skicka null som parameter. |

### Se Även

* klass [PdfToImageOptions](../pdftoimageoptions/)
* namnrymd [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)