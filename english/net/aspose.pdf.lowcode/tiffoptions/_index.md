---
title: "TiffOptions Class"
linktitle: "TiffOptions"
articleTitle: "TiffOptions"
second_title: "Aspose.PDF for .NET"
description: "Represents Pdf to Tiff converter options for the plugin."
type: docs
weight: 1010
url: "/net/aspose.pdf.lowcode/tiffoptions/"
keywords: "TiffOptions, Aspose.Pdf.LowCode, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TiffOptions class

Represents Pdf to [Tiff](../tiff/) converter options for the [`Tiff`](../../aspose.pdf.lowcode/tiff/) plugin.

```csharp
public sealed class TiffOptions : PdfToImageOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TiffOptions](./tiffoptions/#constructor) | Initializes a new instance of the TiffOptions class. |

## Properties

| Name | Description |
| --- | --- |
| [Brightness](./brightness/) { get; set; } | Get or sets a value boundary of the transformation of colors in white and black. |
| [Compression](./compression/) { get; set; } | Gets or sets the type of the compression. |
| [ConversionMode](../../aspose.pdf.lowcode/pdftoimageoptions/conversionmode/) { get; } | Gets image conversion mode. *(Inherited from PdfToImageOptions)* |
| [CoordinateType](./coordinatetype/) { get; set; } | Get or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [Depth](./depth/) { get; set; } | Gets or sets the color depth. |
| [Inputs](../../aspose.pdf.lowcode/pdftoimageoptions/inputs/) { get; } | Returns [`PdfToImage`](../../aspose.pdf.lowcode/pdftoimage/) plugin data collection. *(Inherited from PdfToImageOptions)* |
| [OperationName](./operationname/) { get; } | Returns name of the operation. |
| [OutputResolution](../../aspose.pdf.lowcode/pdftoimageoptions/outputresolution/) { get; set; } | Gets or sets the resolution value of the resulting images. *(Inherited from PdfToImageOptions)* |
| [Outputs](../../aspose.pdf.lowcode/pdftoimageoptions/outputs/) { get; } | *(Inherited from PdfToImageOptions)* |
| [PageList](../../aspose.pdf.lowcode/pdftoimageoptions/pagelist/) { get; set; } | Gets or sets a list of pages for the process. *(Inherited from PdfToImageOptions)* |
| [SaveAsMultiPageTiff](./saveasmultipagetiff/) { get; set; } | Gets and sets flag that allows to save all pages in one multi-page tiff. |
| [Shape](./shape/) { get; set; } | Gets or sets the type of the shape. |
| [SkipBlankPages](./skipblankpages/) { get; set; } | Gets or sets a value indicating whether to skip blank pages. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.lowcode/pdftoimageoptions/addinput/)(*IDataSource*) | Adds new data source to the [`PdfToImage`](../../aspose.pdf.lowcode/pdftoimage/) plugin data collection. *(Inherited from PdfToImageOptions)* |
| [AddOutput](../../aspose.pdf.lowcode/pdftoimageoptions/addoutput/)(*IDataSource*) | Sets new save data source. Can only be a . If you want save images into memory streams, pass null as parameter. *(Inherited from PdfToImageOptions)* |

## Fields

| Name | Description |
| --- | --- |
| const [defaultOutputImageJpegQuality](../../aspose.pdf.lowcode/pdftoimageoptions/defaultoutputimagejpegquality/) | *(Inherited from PdfToImageOptions)* |
| const [defaultOutputImageResolution](../../aspose.pdf.lowcode/pdftoimageoptions/defaultoutputimageresolution/) | *(Inherited from PdfToImageOptions)* |

### See Also

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)

