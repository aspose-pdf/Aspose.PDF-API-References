---
title: Class PdfToImageOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LowCode.PdfToImageOptions class. Represents options for the PdfToImage plugin
type: docs
weight: 7770
url: /net/aspose.pdf.lowcode/pdftoimageoptions/
---
## PdfToImageOptions class

Represents options for the [`PdfToImage`](../pdftoimage/) plugin.

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## Properties

| Name | Description |
| --- | --- |
| [ConversionMode](../../aspose.pdf.lowcode/pdftoimageoptions/conversionmode/) { get; } | Gets image conversion mode. |
| [Inputs](../../aspose.pdf.lowcode/pdftoimageoptions/inputs/) { get; } | Returns [`PdfToImage`](../pdftoimage/) plugin data collection. |
| virtual [OperationName](../../aspose.pdf.lowcode/pdftoimageoptions/operationname/) { get; } | Returns operation name. |
| [OutputResolution](../../aspose.pdf.lowcode/pdftoimageoptions/outputresolution/) { get; set; } | Gets or sets the resolution value of the resulting images. |
| [Outputs](../../aspose.pdf.lowcode/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.lowcode/pdftoimageoptions/pagelist/) { get; set; } | Gets or sets a list of pages for the process. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.lowcode/pdftoimageoptions/addinput/)(IDataSource) | Adds new data source to the [`PdfToImage`](../pdftoimage/) plugin data collection. |
| [AddOutput](../../aspose.pdf.lowcode/pdftoimageoptions/addoutput/)(IDataSource) | Sets new save data source. Can only be a . If you want save images into memory streams, pass null as parameter. |

## Other Members

| Name | Description |
| --- | --- |
| enum [ImageConversionMode](../../aspose.pdf.lowcode/pdftoimageoptions.imageconversionmode) | Defines different modes which can be used while converting from PDF document to Jpeg image. See [`JpegOptions`](../jpegoptions/) class. |

## Remarks

The PdfImageOptions class contains base functions to add data (files, streams) representing input PDF documents.

### See Also

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)


