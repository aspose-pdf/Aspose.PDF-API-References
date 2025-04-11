---
title: Class ImageExtractor
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Plugins.ImageExtractor. تمثل مكون ImageExtractor
type: docs
weight: 8890
url: /ar/net/aspose.pdf.plugins/imageextractor/
---
## ImageExtractor class

تمثل مكون ImageExtractor.

```csharp
public class ImageExtractor : PdfExtractor
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageExtractor](imageextractor/)() | المُنشئ الافتراضي. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | تنفيذ IDisposable. في الواقع، ليس من الضروري لـ PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | يبدأ معالجة PdfExtractor مع المعلمات المحددة. |

## Remarks

يتم استخدام كائن `ImageExtractor` لاستخراج النصوص من مستندات PDF.

## Examples

توضح المثال كيفية استخراج الصور من مستند PDF.

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
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)