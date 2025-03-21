---
title: Class PngOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PngOptions class. Represents Pdf to Png converter options for the Png plugin
type: docs
weight: 9180
url: /net/aspose.pdf.plugins/pngoptions/
---
## PngOptions class

Represents Pdf to Png converter options for the [`Png`](../png/) plugin.

```csharp
public sealed class PngOptions : PdfToImageOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PngOptions](pngoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Gets image conversion mode. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Returns [`PdfToImage`](../pdftoimage/) plugin data collection. |
| override [OperationName](../../aspose.pdf.plugins/pngoptions/operationname/) { get; } | Returns name of the operation. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Gets or sets the resolution value of the resulting images. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Gets or sets a list of pages for the process. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Adds new data source to the [`PdfToImage`](../pdftoimage/) plugin data collection. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Sets new save data source. Can only be a . If you want save images into memory streams, pass null as parameter. |

### See Also

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


