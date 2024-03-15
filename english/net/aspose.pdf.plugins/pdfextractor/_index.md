---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfExtractor class. Represents base functionality to extract text images and other types of content that may occur on the pages of PDF documents
type: docs
weight: 6890
url: /net/aspose.pdf.plugins/pdfextractor/
---
## PdfExtractor class

Represents base functionality to extract text, images, and other types of content that may occur on the pages of PDF documents.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementation of IDisposable. Actually, it is not necessary for PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Starts PdfExtractor processing with the specified parameters. |

## Remarks

The [`TextExtractor`](../textextractor/) object is used to extract text, or [`ImageExtractor`](../imageextractor/) to extract images.

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

### See Also

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


