---
title: Class TextExtractor
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Plugins.TextExtractor. تمثل مكون TextExtractor
type: docs
weight: 9380
url: /ar/net/aspose.pdf.plugins/textextractor/
---
## TextExtractor class

تمثل مكون TextExtractor.

```csharp
public class TextExtractor : PdfExtractor
```

## Constructors

| Name | Description |
| --- | --- |
| [TextExtractor](textextractor/)() | المُنشئ الافتراضي. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | تنفيذ IDisposable. في الواقع، ليس من الضروري لمكون PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | يبدأ معالجة PdfExtractor مع المعلمات المحددة. |

## Remarks

يتم استخدام كائن `TextExtractor` لاستخراج النص في مستندات PDF.

## Examples

توضح المثال كيفية استخراج محتوى النص من مستند PDF.

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