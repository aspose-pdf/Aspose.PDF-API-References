---
title: "Klassen TiffOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Plugins.TiffOptions-klass. Representerar Pdf till Tiff-konverteringsalternativ för Tiff‑pluginet"
type: docs
weight: 9570
url: /sv/net/aspose.pdf.plugins/tiffoptions/
---
## TiffOptions class

Representerar Pdf till Tiff-konverteringsalternativ för [`Tiff`](../tiff/)‑pluginet.

```csharp
public sealed class TiffOptions : PdfToImageOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TiffOptions](tiffoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Brightness](../../aspose.pdf.plugins/tiffoptions/brightness/) { get; set; } | Hämtar eller anger ett värdegräns för färgtransformeringen i vitt och svart. Denna parameter kan tillämpas med EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle eller ColorDepth.Format1bpp == 1 |
| [Compression](../../aspose.pdf.plugins/tiffoptions/compression/) { get; set; } | Hämtar eller anger komprimeringstypen. |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Hämtar bildkonverteringsläge. |
| [CoordinateType](../../aspose.pdf.plugins/tiffoptions/coordinatetype/) { get; set; } | Hämtar eller anger sidkoordinattypen (Media/Crop‑boxar). CropBox‑värdet används som standard. |
| [Depth](../../aspose.pdf.plugins/tiffoptions/depth/) { get; set; } | Hämtar eller anger färgdjupet. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Returnerar [`PdfToImage`](../pdftoimage/)-pluginens datainsamling. |
| override [OperationName](../../aspose.pdf.plugins/tiffoptions/operationname/) { get; } | Returnerar operationens namn. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Hämtar eller anger upplösningsvärdet för de resulterande bilderna. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Hämtar eller anger en lista med sidor för processen. |
| [SaveAsMultiPageTiff](../../aspose.pdf.plugins/tiffoptions/saveasmultipagetiff/) { get; set; } | Hämtar och anger flaggan som möjliggör att spara alla sidor i en flersidig tiff. |
| [Shape](../../aspose.pdf.plugins/tiffoptions/shape/) { get; set; } | Hämtar eller anger typ av formen. |
| [SkipBlankPages](../../aspose.pdf.plugins/tiffoptions/skipblankpages/) { get; set; } | Hämtar eller anger ett värde som indikerar om tomma sidor ska hoppas över. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Lägger till en ny datakälla till [`PdfToImage`](../pdftoimage/)-pluginens datainsamling. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Anger ny sparningsdatakälla. Kan endast vara en . Om du vill spara bilder i minnesströmmar, skicka null som parameter. |

### Se även

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


