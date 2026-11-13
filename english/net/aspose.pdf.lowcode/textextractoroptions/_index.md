---
title: Class TextExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LowCode.TextExtractorOptions class. Represents text extraction options for the TextExtractor plugin
type: docs
weight: 8030
url: /net/aspose.pdf.lowcode/textextractoroptions/
---
## TextExtractorOptions class

Represents text extraction options for the TextExtractor plugin.

```csharp
public sealed class TextExtractorOptions : PdfExtractorOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TextExtractorOptions](textextractoroptions/#constructor)() | Initializes a new instance of the `TextExtractorOptions` object with 'Raw' (default) text formatting mode. |
| [TextExtractorOptions](textextractoroptions/#constructor_1)(TextFormattingMode) | Initializes a new instance of the `TextExtractorOptions` object for the specified text formatting mode. |

## Properties

| Name | Description |
| --- | --- |
| [FormattingMode](../../aspose.pdf.lowcode/textextractoroptions/formattingmode/) { get; } | Gets formatting mode. |
| [Inputs](../../aspose.pdf.lowcode/pdfextractoroptions/inputs/) { get; } | Returns PdfExtractor plugin data collection. |
| override [OperationName](../../aspose.pdf.lowcode/textextractoroptions/operationname/) { get; } | Returns name of the operation. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.lowcode/pdfextractoroptions/addinput/)(IDataSource) | Adds new data source to the PdfExtractor plugin data collection. |

## Other Members

| Name | Description |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.lowcode/textextractoroptions.textformattingmode) | Defines different modes which can be used while converting a PDF document into text. See `TextExtractorOptions` class. |

## Remarks

The `TextExtractorOptions` object is used to set [`TextFormattingMode`](../textextractoroptions.textformattingmode/) and another options for the text extraction operation. Also, it inherits functions to add data (files, streams) representing input PDF documents.

## Examples

The example demonstrates how to extract text content of PDF document.

```csharp
// create TextExtractor object to extract PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions object to set TextFormattingMode (Pure,  or Raw - default)
    extractorOptions = new TextExtractorOptions(TextExtractorOptions.TextFormattingMode.Pure);
    
    // add input file path to data sources
    extractorOptions.AddInput(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(extractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### See Also

* class [PdfExtractorOptions](../pdfextractoroptions/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)


