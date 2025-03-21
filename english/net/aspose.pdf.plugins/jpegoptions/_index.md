---
title: Class JpegOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.JpegOptions class. Represents Pdf to Jpeg converter options for the Jpeg plugin
type: docs
weight: 8920
url: /net/aspose.pdf.plugins/jpegoptions/
---
## JpegOptions class

Represents Pdf to Jpeg converter options for the [`Jpeg`](../jpeg/) plugin.

```csharp
public sealed class JpegOptions : PdfToImageOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [JpegOptions](jpegoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Gets image conversion mode. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Returns [`PdfToImage`](../pdftoimage/) plugin data collection. |
| override [OperationName](../../aspose.pdf.plugins/jpegoptions/operationname/) { get; } | Returns name of the operation. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Gets or sets the resolution value of the resulting images. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Gets or sets a list of pages for the process. |
| [Quality](../../aspose.pdf.plugins/jpegoptions/quality/) { get; set; } | Gets and sets Jpeg quality |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Adds new data source to the [`PdfToImage`](../pdftoimage/) plugin data collection. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Sets new save data source. Can only be a . If you want save images into memory streams, pass null as parameter. |

### See Also

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


