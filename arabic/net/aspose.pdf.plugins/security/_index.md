---
title: "الفئة Security"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.Plugins.Security class. يمثل ملحق Security"
type: docs
weight: 9380
url: /ar/net/aspose.pdf.plugins/security/
---
## Security class

يمثل ملحق `Security`.

```csharp
public sealed class Security : IPlugin
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Security](security/)() | البناء الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Process](../../aspose.pdf.plugins/security/process/)(IPluginOptions) | يبدأ معالجة `Security` بالمعلمات المحددة. |

## أمثلة

يوضح المثال كيفية تشفير مستند PDF.

```csharp
// إنشاء Security
var plugin = new Security();
// إنشاء كائن EncryptionOptions لتعيين التعليمات
var opt = new EncryptionOptions("123456", "qwerty", DocumentPrivilege.ForbidAll));
// إضافة مسار ملف الإدخال
opt.AddInput(new FileDataSource(inputPath));
// تعيين مسار ملف الإخراج
opt.AddOutput(new FileDataSource(outputPath));
// تنفيذ العملية
plugin.Process(opt);
```

يوضح المثال كيفية فك تشفير مستند PDF.

```csharp
// إنشاء Security
var plugin = new Security();
// إنشاء كائن DecryptionOptions لتعيين التعليمات
var opt = new DecryptionOptions("123456"));
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


