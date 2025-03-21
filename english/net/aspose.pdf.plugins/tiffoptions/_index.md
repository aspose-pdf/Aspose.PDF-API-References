---
title: Class TiffOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TiffOptions class. Represents Pdf to Tiff converter options for the Tiff plugin
type: docs
weight: 9420
url: /net/aspose.pdf.plugins/tiffoptions/
---
## TiffOptions class

Represents Pdf to Tiff converter options for the [`Tiff`](../tiff/) plugin.

```csharp
public sealed class TiffOptions : PdfToImageOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TiffOptions](tiffoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Brightness](../../aspose.pdf.plugins/tiffoptions/brightness/) { get; set; } | Get or sets a value boundary of the transformation of colors in white and black. This parameter can be applied with EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle or ColorDepth.Format1bpp == 1 |
| [Compression](../../aspose.pdf.plugins/tiffoptions/compression/) { get; set; } | Gets or sets the type of the compression. |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Gets image conversion mode. |
| [CoordinateType](../../aspose.pdf.plugins/tiffoptions/coordinatetype/) { get; set; } | Get or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [Depth](../../aspose.pdf.plugins/tiffoptions/depth/) { get; set; } | Gets or sets the color depth. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Returns [`PdfToImage`](../pdftoimage/) plugin data collection. |
| override [OperationName](../../aspose.pdf.plugins/tiffoptions/operationname/) { get; } | Returns name of the operation. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Gets or sets the resolution value of the resulting images. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Gets or sets a list of pages for the process. |
| [SaveAsMultiPageTiff](../../aspose.pdf.plugins/tiffoptions/saveasmultipagetiff/) { get; set; } | Gets and sets flag that allows to save all pages in one multi-page tiff. |
| [Shape](../../aspose.pdf.plugins/tiffoptions/shape/) { get; set; } | Gets or sets the type of the shape. |
| [SkipBlankPages](../../aspose.pdf.plugins/tiffoptions/skipblankpages/) { get; set; } | Gets or sets a value indicating whether to skip blank pages. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Adds new data source to the [`PdfToImage`](../pdftoimage/) plugin data collection. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Sets new save data source. Can only be a . If you want save images into memory streams, pass null as parameter. |

### See Also

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


