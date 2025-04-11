---
title: Class TiffOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TiffOptions klass. Representerar Pdf till Tiff konverteringsalternativ för Tiff-plugin
type: docs
weight: 9420
url: /sv/net/aspose.pdf.plugins/tiffoptions/
---
## TiffOptions klass

Representerar Pdf till Tiff konverteringsalternativ för [`Tiff`](../tiff/) plugin.

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
| [Brightness](../../aspose.pdf.plugins/tiffoptions/brightness/) { get; set; } | Hämtar eller ställer in ett värdegräns för transformationen av färger i vitt och svart. Denna parameter kan tillämpas med EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle eller ColorDepth.Format1bpp == 1 |
| [Compression](../../aspose.pdf.plugins/tiffoptions/compression/) { get; set; } | Hämtar eller ställer in typen av kompression. |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Hämtar bildkonverteringsläge. |
| [CoordinateType](../../aspose.pdf.plugins/tiffoptions/coordinatetype/) { get; set; } | Hämtar eller ställer in sidkoordinattype (Media/Crop boxes). CropBox-värdet används som standard. |
| [Depth](../../aspose.pdf.plugins/tiffoptions/depth/) { get; set; } | Hämtar eller ställer in färgdjupet. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Returnerar [`PdfToImage`](../pdftoimage/) plugin datainsamling. |
| override [OperationName](../../aspose.pdf.plugins/tiffoptions/operationname/) { get; } | Returnerar namnet på operationen. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Hämtar eller ställer in upplösningsvärdet för de resulterande bilderna. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Hämtar eller ställer in en lista över sidor för processen. |
| [SaveAsMultiPageTiff](../../aspose.pdf.plugins/tiffoptions/saveasmultipagetiff/) { get; set; } | Hämtar och ställer in en flagga som tillåter att spara alla sidor i en fler-sidig tiff. |
| [Shape](../../aspose.pdf.plugins/tiffoptions/shape/) { get; set; } | Hämtar eller ställer in typen av formen. |
| [SkipBlankPages](../../aspose.pdf.plugins/tiffoptions/skipblankpages/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om tomma sidor ska hoppas över. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Lägger till en ny datakälla till [`PdfToImage`](../pdftoimage/) plugin datainsamling. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Ställer in ny spara datakälla. Kan endast vara en . Om du vill spara bilder i minnesströmmar, skicka null som parameter. |

### Se Även

* klass [PdfToImageOptions](../pdftoimageoptions/)
* namnrymd [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)