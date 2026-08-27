---
title: "الفئة Signature"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Plugins.Signature. تمثل المكوّن Signature"
type: docs
weight: 9410
url: /ar/net/aspose.pdf.plugins/signature/
---
## Signature class

تمثل المكوّن `Signature`.

```csharp
public sealed class Signature : IPlugin
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Signature](signature/)() | البناء الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | يبدأ معالجة `Signature` بالمعلمات المحددة. |

## أمثلة

يوضح المثال كيفية توقيع مستند PDF.

```csharp
// إنشاء Signature
var plugin = new Signature();
// إنشاء كائن SignOptions لتعيين التعليمات
var opt = new SignOptions(inputPfx, inputPfxPassword);
// إضافة مسار ملف الإدخال
opt.AddInput(new FileDataSource(inputPath));
// تعيين مسار ملف الإخراج
opt.AddOutput(new FileDataSource(outputPath));
// تنفيذ العملية
plugin.Process(opt);
```

### انظر أيضًا

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


