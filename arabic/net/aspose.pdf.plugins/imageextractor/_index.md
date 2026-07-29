---
title: "الفئة ImageExtractor"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Plugins.ImageExtractor. تمثل ملحق ImageExtractor"
type: docs
weight: 9020
url: /ar/net/aspose.pdf.plugins/imageextractor/
---
## ImageExtractor class

يمثل المكوّن الإضافي ImageExtractor.

```csharp
public class ImageExtractor : PdfExtractor
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ImageExtractor](imageextractor/)() | البناء الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | تنفيذ IDisposable. في الواقع، ليس ضرورياً لـ PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | يبدأ معالجة PdfExtractor بالمعلمات المحددة. |

## ملاحظات

يُستخدم كائن `ImageExtractor` لاستخراج النص في مستندات PDF.

## أمثلة

يوضح المثال كيفية استخراج الصور من مستند PDF.

```csharp
// إنشاء كائن ImageExtractor لاستخراج الصور
using (ImageExtractor extractor = new ImageExtractor())
{
    // إنشاء ImageExtractorOptions
    imageExtractorOptions = new ImageExtractorOptions();
    
    // إضافة مسار ملف الإدخال إلى مصادر البيانات
    imageExtractor.AddDataSource(new FileDataSource(inputPath));
    
    // تنفيذ عملية الاستخراج
    ResultContainer resultContainer = extractor.Process(imageExtractorOptions);
    
    // احصل على الصورة من كائن ResultContainer
    var imageExtracted = resultContainer.ResultCollection[0].ToFile();
}
```

### انظر أيضًا

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


