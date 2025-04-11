---
title: Class PdfToImageOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfToImageOptions klass. Representerar alternativ för PdfToImage-plugin
type: docs
weight: 9130
url: /sv/net/aspose.pdf.plugins/pdftoimageoptions/
---
## PdfToImageOptions klass

Representerar alternativ för [`PdfToImage`](../pdftoimage/) plugin.

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Hämtar bildkonverteringsläge. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Returnerar datainsamling för [`PdfToImage`](../pdftoimage/) plugin. |
| virtual [OperationName](../../aspose.pdf.plugins/pdftoimageoptions/operationname/) { get; } | Returnerar operationsnamn. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Hämtar eller ställer in upplösningsvärdet för de resulterande bilderna. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Hämtar eller ställer in en lista över sidor för processen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Lägger till ny datakälla till datainsamlingen för [`PdfToImage`](../pdftoimage/) plugin. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Ställer in ny sparad datakälla. Kan endast vara en . Om du vill spara bilder i minnesströmmar, skicka null som parameter. |

## Andra Medlemmar

| Namn | Beskrivning |
| --- | --- |
| enum [ImageConversionMode](../../aspose.pdf.plugins/pdftoimageoptions.imageconversionmode) | Definierar olika lägen som kan användas vid konvertering från PDF-dokument till Jpeg-bild. Se [`JpegOptions`](../jpegoptions/) klass. |

## Anmärkningar

PdfImageOptions-klassen innehåller grundläggande funktioner för att lägga till data (filer, strömmar) som representerar inmatnings-PDF-dokument.

### Se Även

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)