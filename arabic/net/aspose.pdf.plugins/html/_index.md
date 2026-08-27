---
title: "الفئة Html"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Plugins.Html. تمثّل ملحق Html"
type: docs
weight: 8950
url: /ar/net/aspose.pdf.plugins/html/
---
## Html class

يمثّل ملحق `Html`.

```csharp
public sealed class Html : IDisposable, IPlugin
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Html](html/)() | البناء الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/html/dispose/)() | تنفيذ IDisposable. |
| [Process](../../aspose.pdf.plugins/html/process/)(IPluginOptions) | يبدأ معالجة `Html` بالمعلمات المحددة. |

## أمثلة

يوضح المثال كيفية تحويل PDF إلى مستند HTML.

```csharp
// إنشاء Html
var converter = new Html();
// إنشاء كائن PdfToHtmlOptions لتعيين نوع بيانات الإخراج كملف مع موارد مدمجة
var opt = new PdfToHtmlOptions(PdfToHtmlOptions.SaveDataType.FileWithEmbeddedResources);
// إضافة مسار ملف الإدخال
opt.AddInput(new FileDataSource(inputPath));
// تعيين مسار ملف الإخراج
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

يوضح المثال كيفية تحويل HTML إلى مستند PDF.

```csharp
// إنشاء Html
var converter = new Html();
// إنشاء HtmlToPdfOptions
var opt = new HtmlToPdfOptions();
// إضافة مسار ملف الإدخال
opt.AddInput(new FileDataSource(inputPath));
// تعيين مسار ملف الإخراج
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### انظر أيضًا

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


