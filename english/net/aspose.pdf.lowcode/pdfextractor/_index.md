---
title: "PdfExtractor Class"
linktitle: "PdfExtractor"
articleTitle: "PdfExtractor"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.PdfExtractor class. Represents base functionality to extract text, images, and other types of content that may occur on the pages of PDF d..."
type: docs
weight: 650
url: "/net/aspose.pdf.lowcode/pdfextractor/"
keywords: "PdfExtractor, Aspose.Pdf.LowCode, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfExtractor class

Represents base functionality to extract text, images, and other types of content that may occur on the pages of PDF documents.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## Examples

The example demonstrates how to extract text content of PDF document.

```csharp
// create TextExtractor object to extract PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions object to set instructions
    textExtractorOptions = new TextExtractorOptions();

    // add input file path to data sources
    textExtractorOptions.AddInput(new FileDataSource(inputPath));

    // perform extraction process
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);

    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

## Methods

| Name | Description |
| --- | --- |
| [Dispose](./dispose/)() | Implementation of IDisposable. Actually, it is not necessary for PdfExtractor. |
| [Process](./process/)(IPluginOptions) | Starts PdfExtractor processing with the specified parameters. |

## Remarks

The [`TextExtractor`](../../aspose.pdf.lowcode/textextractor/) object is used to extract text, or [`ImageExtractor`](../../aspose.pdf.lowcode/imageextractor/) to extract images.

### See Also

* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)

