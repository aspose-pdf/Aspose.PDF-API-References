---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Plugins.PdfExtractor. تمثل الوظائف الأساسية لاستخراج النصوص والصور وأنواع أخرى من المحتوى التي قد تحدث في صفحات مستندات PDF
type: docs
weight: 9060
url: /ar/net/aspose.pdf.plugins/pdfextractor/
---
## PdfExtractor class

تمثل الوظائف الأساسية لاستخراج النصوص والصور وأنواع أخرى من المحتوى التي قد تحدث في صفحات مستندات PDF.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | تنفيذ IDisposable. في الواقع، ليس من الضروري لفئة PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | يبدأ معالجة PdfExtractor مع المعلمات المحددة. |

## Remarks

يتم استخدام كائن [`TextExtractor`](../textextractor/) لاستخراج النصوص، أو [`ImageExtractor`](../imageextractor/) لاستخراج الصور.

## Examples

المثال يوضح كيفية استخراج محتوى النص من مستند PDF.

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