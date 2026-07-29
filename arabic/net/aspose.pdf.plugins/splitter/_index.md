---
title: "الفئة Splitter"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Plugins.Splitter. تمثل ملحق Splitter."
type: docs
weight: 9430
url: /ar/net/aspose.pdf.plugins/splitter/
---
## Splitter class

تمثل ملحق `Splitter`.

```csharp
public class Splitter : IPlugin
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Splitter](splitter/)() | البناء الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Process](../../aspose.pdf.plugins/splitter/process/)(IPluginOptions) | يبدأ معالجة `Splitter` بالمعلمات المحددة. |

## أمثلة

يوضح المثال كيفية تقسيم مستند PDF.

```csharp
// إنشاء Splitter
var splitter = new Splitter();
// إنشاء كائن SplitOptions لتعيين التعليمات
var opt = new SplitOptions();
// إضافة مسارات ملفات الإدخال
opt.AddInput(new FileDataSource(inputPath));
// تعيين مسارات ملفات الإخراج
opt.AddOutput(new FileDataSource(outputPath1));
opt.AddOutput(new FileDataSource(outputPath2));
// تنفيذ العملية
splitter.Process(opt);
```

### انظر أيضًا

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


