---
title: "TextExtractor Class"
linktitle: "TextExtractor"
articleTitle: "TextExtractor"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.TextExtractor class. Represents TextExtractor plugin."
type: docs
weight: 970
url: "/net/aspose.pdf.lowcode/textextractor/"
keywords: "TextExtractor, Aspose.Pdf.LowCode, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TextExtractor class

Represents TextExtractor plugin.

```csharp
public class TextExtractor : PdfExtractor
```

## Examples

The example demonstrates how to extract text content of PDF document.

```csharp
// create TextExtractor object to extract text in PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions
    textExtractorOptions = new TextExtractorOptions();

    // add input file path to data sources
    textExtractorOptions.AddDataSource(new FileDataSource(inputPath));

    // perform extraction process
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);

    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

## Constructors

| Name | Description |
| --- | --- |
| [TextExtractor](./textextractor/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.lowcode/pdfextractor/dispose/)() | Implementation of IDisposable. Actually, it is not necessary for PdfExtractor. |
| [Process](../../aspose.pdf.lowcode/pdfextractor/process/)(IPluginOptions) | Starts PdfExtractor processing with the specified parameters. |

## Remarks

The [`TextExtractor`](../../aspose.pdf.lowcode/textextractor/) object is used to extract text in PDF documents.

### See Also

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)

