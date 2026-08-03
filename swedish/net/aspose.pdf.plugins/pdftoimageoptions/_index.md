---
title: "Klassen PdfToImageOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Plugins.PdfToImageOptions-klass. Representerar alternativ för PdfToImage‑plugin"
type: docs
weight: 9280
url: /sv/net/aspose.pdf.plugins/pdftoimageoptions/
---
## PdfToImageOptions class

Representerar alternativ för [`PdfToImage`](../pdftoimage/)‑plugin.

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Hämtar bildkonverteringsläge. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Returnerar [`PdfToImage`](../pdftoimage/)-pluginens datainsamling. |
| virtual [OperationName](../../aspose.pdf.plugins/pdftoimageoptions/operationname/) { get; } | Returnerar operationens namn. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Hämtar eller anger upplösningsvärdet för de resulterande bilderna. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Hämtar eller anger en lista med sidor för processen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Lägger till en ny datakälla till [`PdfToImage`](../pdftoimage/)-pluginens datainsamling. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Anger ny sparningsdatakälla. Kan endast vara en . Om du vill spara bilder i minnesströmmar, skicka null som parameter. |

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| enum [ImageConversionMode](../../aspose.pdf.plugins/pdftoimageoptions.imageconversionmode) | Definierar olika lägen som kan användas vid konvertering från PDF‑dokument till Jpeg‑bild. Se [`JpegOptions`](../jpegoptions/)‑klassen. |

## Anmärkningar

PdfImageOptions‑klassen innehåller grundfunktioner för att lägga till data (filer, strömmar) som representerar indata‑PDF‑dokument.

### Se även

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


