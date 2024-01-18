---
title: Class PdfExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfExtractorOptions class. Represents options for the TextExtractor and ImageExtractor plugins
type: docs
weight: 6810
url: /net/aspose.pdf.plugins/pdfextractoroptions/
---
## PdfExtractorOptions class

Represents options for the TextExtractor and ImageExtractor plugins.

```csharp
public abstract class PdfExtractorOptions : IPluginOptions
```

## Properties

| Name | Description |
| --- | --- |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | Returns PdfExtractor plugin data collection. |
| virtual [OperationName](../../aspose.pdf.plugins/pdfextractoroptions/operationname/) { get; } | Returns operation name |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | Adds new data source to the PdfExtractor plugin data collection. |

## Remarks

The `PdfExtractorOptions` contains base functions to add data (files, streams) representing input PDF documents. Please create [`TextExtractorOptions`](../textextractoroptions/) or ImageExtractorOptions instead of this.

### See Also

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


