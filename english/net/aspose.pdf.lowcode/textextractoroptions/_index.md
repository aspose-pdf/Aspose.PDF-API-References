---
title: "TextExtractorOptions Class"
linktitle: "TextExtractorOptions"
articleTitle: "TextExtractorOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.TextExtractorOptions class. Represents text extraction options for the TextExtractor plugin."
type: docs
weight: 980
url: "/net/aspose.pdf.lowcode/textextractoroptions/"
keywords: "TextExtractorOptions, Aspose.Pdf.LowCode, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TextExtractorOptions class

Represents text extraction options for the [TextExtractor](../textextractor/) plugin.

```csharp
public sealed class TextExtractorOptions : PdfExtractorOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TextExtractorOptions](./textextractoroptions/#constructor)() | Initializes a new instance of the [`TextExtractorOptions`](../../aspose.pdf.lowcode/textextractoroptions/) object with 'Raw' (default) text formatting mode. |
| [TextExtractorOptions](./textextractoroptions/#constructor_1)(TextFormattingMode) | Initializes a new instance of the [`TextExtractorOptions`](../../aspose.pdf.lowcode/textextractoroptions/) object for the specified text formatting mode. |

## Properties

| Name | Description |
| --- | --- |
| [FormattingMode](./formattingmode/) { get; } | Gets formatting mode. |
| [Inputs](../../aspose.pdf.lowcode/pdfextractoroptions/inputs/) { get; } | Returns PdfExtractor plugin data collection. |
| override [OperationName](./operationname/) { get; } | Returns name of the operation. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.lowcode/pdfextractoroptions/addinput/)(IDataSource) | Adds new data source to the PdfExtractor plugin data collection. |

## Other Members

| Name | Description |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.lowcode/textextractoroptions.textformattingmode) | Defines different modes which can be used while converting a PDF document into text. See [`TextExtractorOptions`](../../aspose.pdf.lowcode/textextractoroptions/) class. |

## Remarks

The [`TextExtractorOptions`](../../aspose.pdf.lowcode/textextractoroptions/) object is used to set `TextFormattingMode` and another options for the text extraction operation.
 Also, it inherits functions to add data (files, streams) representing input PDF documents.

### See Also

* class [PdfExtractorOptions](../pdfextractoroptions/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)

