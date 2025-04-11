---
title: Class Security
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Plugins.Security. تمثل مكون الأمان
type: docs
weight: 9230
url: /ar/net/aspose.pdf.plugins/security/
---
## فئة الأمان

تمثل مكون `Security`.

```csharp
public sealed class Security : IPlugin
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Security](security/)() | المنشئ الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Process](../../aspose.pdf.plugins/security/process/)(IPluginOptions) | يبدأ معالجة `Security` مع المعلمات المحددة. |

## أمثلة

المثال يوضح كيفية تشفير مستند PDF.

```csharp
// create Security 
var plugin = new Security();
// create EncryptionOptions object to set instructions
var opt = new EncryptionOptions("123456", "qwerty", DocumentPrivilege.ForbidAll));
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

المثال يوضح كيفية فك تشفير مستند PDF.

```csharp
// create Security 
var plugin = new Security();
// create DecryptionOptions object to set instructions
var opt = new DecryptionOptions("123456"));
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

### انظر أيضًا

* واجهة [IPlugin](../iplugin/)
* مساحة الأسماء [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* التجميع [Aspose.PDF](../../)