---
title: "الفئة Optimizer"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.Plugins.Optimizer فئة. تمثّل ملحق Optimizer"
type: docs
weight: 9120
url: /ar/net/aspose.pdf.plugins/optimizer/
---
## Optimizer class

تمثّل ملحق `Optimizer`.

```csharp
public sealed class Optimizer : IPlugin
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Optimizer](optimizer/)() | البناء الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Process](../../aspose.pdf.plugins/optimizer/process/)(IPluginOptions) | يبدأ معالجة `Optimizer` بالمعلمات المحددة. |

## أمثلة

يوضح المثال كيفية تحسين مستند PDF.

```csharp
// إنشاء Optimizer
var optimizer = new Optimizer();
// إنشاء كائن OptimizeOptions لتعيين التعليمات
var opt = new OptimizeOptions();
// إضافة مسارات ملفات الإدخال
opt.AddInput(new FileDataSource(inputPath));
// تعيين مسار ملف الإخراج
opt.AddOutput(new FileDataSource(outputPath));
// تنفيذ العملية
optimizer.Process(opt);
```

### انظر أيضًا

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


