---
title: "PdfToImageOptions Class"
linktitle: "PdfToImageOptions"
articleTitle: "PdfToImageOptions"
second_title: "Aspose.PDF for .NET"
description: "Represents options for the plugin."
type: docs
weight: 720
url: "/net/aspose.pdf.lowcode/pdftoimageoptions/"
keywords: "PdfToImageOptions, Aspose.Pdf.LowCode, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfToImageOptions class

Represents options for the [`PdfToImage`](../../aspose.pdf.lowcode/pdftoimage/) plugin.

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## Properties

| Name | Description |
| --- | --- |
| [ConversionMode](./conversionmode/) { get; } | Gets image conversion mode. |
| [Inputs](./inputs/) { get; } | Returns [`PdfToImage`](../../aspose.pdf.lowcode/pdftoimage/) plugin data collection. |
| [OperationName](./operationname/) { get; } | Returns operation name. |
| [OutputResolution](./outputresolution/) { get; set; } | Gets or sets the resolution value of the resulting images. |
| [Outputs](./outputs/) { get; } |  |
| [PageList](./pagelist/) { get; set; } | Gets or sets a list of pages for the process. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](./addinput/)(*IDataSource*) | Adds new data source to the [`PdfToImage`](../../aspose.pdf.lowcode/pdftoimage/) plugin data collection. |
| [AddOutput](./addoutput/)(*IDataSource*) | Sets new save data source. Can only be a . If you want save images into memory streams, pass null as parameter. |

## Fields

| Name | Description |
| --- | --- |
| const [defaultOutputImageJpegQuality](./defaultoutputimagejpegquality/) |  |
| const [defaultOutputImageResolution](./defaultoutputimageresolution/) |  |

## Remarks

The PdfImageOptions class contains base functions to add data (files, streams) representing input PDF documents.

### See Also

* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)

