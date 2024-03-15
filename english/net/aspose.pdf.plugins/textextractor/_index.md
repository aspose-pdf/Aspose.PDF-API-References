---
title: Class TextExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TextExtractor class. Represents TextExtractor plugin
type: docs
weight: 7190
url: /net/aspose.pdf.plugins/textextractor/
---
## TextExtractor class

Represents TextExtractor plugin.

```csharp
public class TextExtractor : PdfExtractor
```

## Constructors

| Name | Description |
| --- | --- |
| [TextExtractor](textextractor/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementation of IDisposable. Actually, it is not necessary for PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Starts PdfExtractor processing with the specified parameters. |

## Remarks

The `TextExtractor` object is used to extract text in PDF documents.

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

### See Also

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


