---
title: "الفئة Merger"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Plugins.Merger. تمثّل مكوّن Merger"
type: docs
weight: 9070
url: /ar/net/aspose.pdf.plugins/merger/
---
## Merger class

تمثّل مكوّن `Merger`.

```csharp
public sealed class Merger : IPlugin
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Merger](merger/)() | البناء الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Process](../../aspose.pdf.plugins/merger/process/)(IPluginOptions) | يبدأ معالجة `Merger` بالمعلمات المحددة. |

## أمثلة

يوضح المثال كيفية دمج مستندين PDF.

```csharp
// إنشاء Merger
var merger = new Merger();
// إنشاء كائن MergeOptions لتحديد التعليمات
var opt = new MergeOptions();
// إضافة مسارات ملفات الإدخال
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// تعيين مسار ملف الإخراج
opt.AddOutput(new FileDataSource(outputPath));
// تنفيذ العملية
merger.Process(opt);
```

### انظر أيضًا

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


