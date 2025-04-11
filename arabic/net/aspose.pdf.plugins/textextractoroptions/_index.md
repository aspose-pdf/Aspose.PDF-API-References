---
title: Class TextExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TextExtractorOptions class. يمثل خيارات استخراج النص لملحق TextExtractor
type: docs
weight: 9390
url: /ar/net/aspose.pdf.plugins/textextractoroptions/
---
## TextExtractorOptions class

يمثل خيارات استخراج النص لملحق TextExtractor.

```csharp
public sealed class TextExtractorOptions : PdfExtractorOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TextExtractorOptions](textextractoroptions/#constructor)() | يقوم بتهيئة مثيل جديد من كائن `TextExtractorOptions` مع وضع تنسيق النص 'Raw' (افتراضي). |
| [TextExtractorOptions](textextractoroptions/#constructor_1)(TextFormattingMode) | يقوم بتهيئة مثيل جديد من كائن `TextExtractorOptions` لوضع تنسيق النص المحدد. |

## Properties

| Name | Description |
| --- | --- |
| [FormattingMode](../../aspose.pdf.plugins/textextractoroptions/formattingmode/) { get; } | يحصل على وضع التنسيق. |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | يعيد مجموعة بيانات ملحق PdfExtractor. |
| override [OperationName](../../aspose.pdf.plugins/textextractoroptions/operationname/) { get; } | يعيد اسم العملية. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | يضيف مصدر بيانات جديد إلى مجموعة بيانات ملحق PdfExtractor. |

## Other Members

| Name | Description |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | يحدد أوضاع مختلفة يمكن استخدامها أثناء تحويل مستند PDF إلى نص. انظر كلاس `TextExtractorOptions`. |

## Remarks

يستخدم كائن `TextExtractorOptions` لتعيين [`TextFormattingMode`](../textextractoroptions.textformattingmode/) وخيارات أخرى لعملية استخراج النص. كما أنه يرث وظائف لإضافة بيانات (ملفات، تدفقات) تمثل مستندات PDF المدخلة.

## Examples

المثال يوضح كيفية استخراج محتوى النص من مستند PDF.

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
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)