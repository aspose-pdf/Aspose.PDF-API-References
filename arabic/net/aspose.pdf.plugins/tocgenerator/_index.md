---
title: "الفئة TocGenerator"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Plugins.TocGenerator. تمثل مكوّن Aspose.PDF TocGenerator"
type: docs
weight: 9580
url: /ar/net/aspose.pdf.plugins/tocgenerator/
---
## TocGenerator class

يمثل ملحق Aspose.PDF TocGenerator.

```csharp
public sealed class TocGenerator : IDisposable, IPlugin
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TocGenerator](tocgenerator/)() | البناء الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | تنفيذ IDisposable. في الواقع، ليس ضرورياً لـ TocGenerator. |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | يبدأ معالجة PdfGenerator باستخدام المعلمات المحددة. |

## أمثلة

يوضح المثال كيفية إضافة فهرس (TOC) إلى ملف PDF.

```csharp
// إنشاء TocGenerator
var generator = new TocGenerator();
// إنشاء كائن TocOptions لتعيين التعليمات
var opt = new TocOptions();
// إضافة مسارات ملفات الإدخال
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// تعيين مسار ملف الإخراج
opt.AddOutput(new FileDataSource(outputPath));
// تنفيذ عملية الاستخراج
generator.Process(opt);
```

### انظر أيضًا

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


