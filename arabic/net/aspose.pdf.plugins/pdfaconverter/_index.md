---
title: "فئة PdfAConverter"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Plugins.PdfAConverter. تمثل إضافة لمعالجة تحويل مستندات PDF إلى تنسيق PDF/A وللتحقق من توافق PDF/A"
type: docs
weight: 9150
url: /ar/net/aspose.pdf.plugins/pdfaconverter/
---
## PdfAConverter class

يمثل ملحقًا لمعالجة تحويل مستندات PDF إلى تنسيق PDF/A وللتحقق من توافق PDF/A.

```csharp
public sealed class PdfAConverter : IPlugin
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfAConverter](pdfaconverter/)() | البناء الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Process](../../aspose.pdf.plugins/pdfaconverter/process/)(IPluginOptions) | يبدأ عملية تحويل أو تحقق PDF/A باستخدام الخيارات المحددة. |

## أمثلة

يوضح المثال كيفية التحقق من توافق مستند PDF مع تنسيق PDF/A (PDF/A-1a في هذه الحالة):

```csharp
// إنشاء فئة الخيارات لإعداد عملية التحقق
var options = new PdfAValidateOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_1A
};

// إضافة ملف واحد أو أكثر للتحقق
options.AddInput(new FileDataSource("path_to_your_first_pdf_file.pdf")); // replace with your actual file path
options.AddInput(new FileDataSource("path_to_your_second_pdf_file.pdf"));
// أضف المزيد من الملفات حسب الحاجة

// إنشاء مثيل الإضافة
var plugin = new PdfAConverter();

// تشغيل التحقق والحصول على النتائج
var resultContainer = plugin.Process(options);

// تحقق من خاصية resultContainer.ResultCollection للحصول على نتائج التحقق لكل ملف:
for (var i = 0; i < resultContainer.ResultCollection.Count; i++)
{
    var result = resultContainer.ResultCollection[i];
    var validationResult = (PdfAValidationResult) result.Data;
    var isValid = validationResult.IsValid; // Validation result for the i-th document
}
```

يوضح المثال كيفية تحويل مستند PDF إلى تنسيق PDF/A (PDF/A-3b في هذه الحالة):

```csharp
// إنشاء فئة الخيارات لإعداد عملية التحويل
var options = new PdfAConvertOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_3B
};

// إضافة ملف المصدر
options.AddInput(new FileDataSource("path_to_your_pdf_file.pdf")); // replace with your actual file path

// إضافة المسار لحفظ الملف المحول
options.AddOutput(new FileDataSource("path_to_the_converted_file.pdf"));

// إنشاء مثيل الإضافة
var plugin = new PdfAConverter();

// تشغيل التحويل
plugin.Process(options);
```

### انظر أيضًا

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


