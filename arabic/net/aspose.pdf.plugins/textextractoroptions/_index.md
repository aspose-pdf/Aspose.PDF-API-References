---
title: "الفئة TextExtractorOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Plugins.TextExtractorOptions. تمثل خيارات استخراج النص لملحق TextExtractor."
type: docs
weight: 9540
url: /ar/net/aspose.pdf.plugins/textextractoroptions/
---
## TextExtractorOptions class

يمثل خيارات استخراج النص لملحق TextExtractor.

```csharp
public sealed class TextExtractorOptions : PdfExtractorOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextExtractorOptions](textextractoroptions/#constructor)() | ينشئ نسخة جديدة من كائن `TextExtractorOptions` مع وضع تنسيق النص 'Raw' (الافتراضي). |
| [TextExtractorOptions](textextractoroptions/#constructor_1)(TextFormattingMode) | يُنشئ مثيلاً جديدًا لكائن `TextExtractorOptions` لوضع تنسيق النص المحدد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [FormattingMode](../../aspose.pdf.plugins/textextractoroptions/formattingmode/) { get; } | يحصل على وضع التنسيق. |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | يعيد مجموعة بيانات إضافة PdfExtractor. |
| override [OperationName](../../aspose.pdf.plugins/textextractoroptions/operationname/) { get; } | يرجع اسم العملية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | يضيف مصدر بيانات جديد إلى مجموعة بيانات إضافة PdfExtractor. |

## الأعضاء الآخرين

| الاسم | الوصف |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | يحدد أوضاعًا مختلفة يمكن استخدامها أثناء تحويل مستند PDF إلى نص. راجع فئة `TextExtractorOptions`. |

## ملاحظات

يُستخدم كائن `TextExtractorOptions` لتعيين [`TextFormattingMode`](../textextractoroptions.textformattingmode/) وخيارات أخرى لعملية استخراج النص. كما أنه يرث وظائف لإضافة البيانات (ملفات، تدفقات) التي تمثل مستندات PDF المدخلة.

## أمثلة

يوضح المثال كيفية استخراج محتوى النص من مستند PDF.

```csharp
// إنشاء كائن TextExtractor لاستخراج محتويات PDF
using (TextExtractor extractor = new TextExtractor())
{
    // إنشاء كائن TextExtractorOptions لتعيين TextFormattingMode (Pure أو Raw - الافتراضي)
    extractorOptions = new TextExtractorOptions(TextExtractorOptions.TextFormattingMode.Pure);
    
    // إضافة مسار ملف الإدخال إلى مصادر البيانات
    extractorOptions.AddInput(new FileDataSource(inputPath));
    
    // تنفيذ عملية الاستخراج
    ResultContainer resultContainer = extractor.Process(extractorOptions);
    
    // الحصول على النص المستخرج من كائن ResultContainer
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### انظر أيضًا

* class [PdfExtractorOptions](../pdfextractoroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


