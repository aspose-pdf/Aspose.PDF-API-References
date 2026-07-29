---
title: "الفئة TextExtractor"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Plugins.TextExtractor. تمثل مكوّن TextExtractor الإضافي"
type: docs
weight: 9530
url: /ar/net/aspose.pdf.plugins/textextractor/
---
## TextExtractor class

يمثل ملحق TextExtractor.

```csharp
public class TextExtractor : PdfExtractor
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextExtractor](textextractor/)() | البناء الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | تنفيذ IDisposable. في الواقع، ليس ضرورياً لـ PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | يبدأ معالجة PdfExtractor بالمعلمات المحددة. |

## ملاحظات

يُستخدم كائن `TextExtractor` لاستخراج النص في مستندات PDF.

## أمثلة

يوضح المثال كيفية استخراج محتوى النص من مستند PDF.

```csharp
// إنشاء كائن TextExtractor لاستخراج النص في محتويات PDF
using (TextExtractor extractor = new TextExtractor())
{
    // إنشاء TextExtractorOptions
    textExtractorOptions = new TextExtractorOptions();
    
    // إضافة مسار ملف الإدخال إلى مصادر البيانات
    textExtractorOptions.AddDataSource(new FileDataSource(inputPath));
    
    // تنفيذ عملية الاستخراج
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // الحصول على النص المستخرج من كائن ResultContainer
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### انظر أيضًا

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


