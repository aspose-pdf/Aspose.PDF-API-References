---
title: Class ImageExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LowCode.ImageExtractor class. Represents ImageExtractor plugin
type: docs
weight: 7510
url: /net/aspose.pdf.lowcode/imageextractor/
---
## ImageExtractor class

Represents ImageExtractor plugin.

```csharp
public class ImageExtractor : PdfExtractor
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageExtractor](imageextractor/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.lowcode/pdfextractor/dispose/)() | Implementation of IDisposable. Actually, it is not necessary for PdfExtractor. |
| [Process](../../aspose.pdf.lowcode/pdfextractor/process/)(IPluginOptions) | Starts PdfExtractor processing with the specified parameters. |

## Remarks

The `ImageExtractor` object is used to extract text in PDF documents.

## Examples

The example demonstrates how to extract images from PDF document.

```csharp
// create ImageExtractor object to extract images
using (ImageExtractor extractor = new ImageExtractor())
{
    // create ImageExtractorOptions
    imageExtractorOptions = new ImageExtractorOptions();
    
    // add input file path to data sources
    imageExtractor.AddDataSource(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(imageExtractorOptions);
    
    // get the image from the ResultContainer object
    var imageExtracted = resultContainer.ResultCollection[0].ToFile();
}
```

### See Also

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)


