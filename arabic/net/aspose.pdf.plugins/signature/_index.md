---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Plugins.Signature. تمثل مكون التوقيع
type: docs
weight: 9260
url: /ar/net/aspose.pdf.plugins/signature/
---
## فئة التوقيع

تمثل مكون `Signature`.

```csharp
public sealed class Signature : IPlugin
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Signature](signature/)() | المنشئ الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | يبدأ معالجة `Signature` مع المعلمات المحددة. |

## أمثلة

توضح المثال كيفية توقيع مستند PDF.

```csharp
// create Signature
var plugin = new Signature();
// create SignOptions object to set instructions
var opt = new SignOptions(inputPfx, inputPfxPassword);
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

### انظر أيضًا

* الواجهة [IPlugin](../iplugin/)
* مساحة الاسم [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* التجميع [Aspose.PDF](../../)