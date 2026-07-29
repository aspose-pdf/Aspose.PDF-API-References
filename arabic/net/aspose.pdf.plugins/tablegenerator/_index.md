---
title: "الفئة TableGenerator"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Plugins.TableGenerator. تمثل مكوّن Aspose.PDF TableGenerator الإضافي"
type: docs
weight: 9500
url: /ar/net/aspose.pdf.plugins/tablegenerator/
---
## TableGenerator class

يمثل ملحق Aspose.PDF TableGenerator.

```csharp
public sealed class TableGenerator : IDisposable, IPlugin
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TableGenerator](tablegenerator/)() | البناء الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | تنفيذ IDisposable. في الواقع، ليس ضرورياً لـ TableGenerator. |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | يبدأ معالجة PdfGenerator باستخدام المعلمات المحددة. |

## أمثلة

المثال يوضح كيفية إضافة جدول إلى ملف PDF.

```csharp
// إنشاء TableGenerator
var generator = new TableGenerator();
// إنشاء كائن TableOptions لتعيين التعليمات
var opt = new TableOptions();
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


