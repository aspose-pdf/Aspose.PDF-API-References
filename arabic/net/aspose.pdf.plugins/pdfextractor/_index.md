---
title: "فئة PdfExtractor"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Plugins.PdfExtractor. يمثل الوظيفة الأساسية لاستخراج النصوص والصور وأنواع أخرى من المحتوى التي قد تظهر على صفحات مستندات PDF."
type: docs
weight: 9210
url: /ar/net/aspose.pdf.plugins/pdfextractor/
---
## PdfExtractor class

يمثل الوظيفة الأساسية لاستخراج النصوص والصور وأنواع أخرى من المحتوى التي قد تظهر في صفحات مستندات PDF.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | تنفيذ IDisposable. في الواقع، ليس ضرورياً لـ PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | يبدأ معالجة PdfExtractor بالمعلمات المحددة. |

## ملاحظات

الكائن [`TextExtractor`](../textextractor/) يُستخدم لاستخراج النص، أو [`ImageExtractor`](../imageextractor/) لاستخراج الصور.

## أمثلة

يوضح المثال كيفية استخراج محتوى النص من مستند PDF.

```csharp
// إنشاء كائن TextExtractor لاستخراج محتويات PDF
using (TextExtractor extractor = new TextExtractor())
{
    // إنشاء كائن TextExtractorOptions لتعيين التعليمات
    textExtractorOptions = new TextExtractorOptions();
    
    // إضافة مسار ملف الإدخال إلى مصادر البيانات
    textExtractorOptions.AddInput(new FileDataSource(inputPath));
    
    // تنفيذ عملية الاستخراج
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // الحصول على النص المستخرج من كائن ResultContainer
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### انظر أيضًا

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


