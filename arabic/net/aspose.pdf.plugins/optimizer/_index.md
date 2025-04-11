---
title: Class Optimizer
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Plugins.Optimizer. تمثل مُحسّن الإضافات
type: docs
weight: 8970
url: /ar/net/aspose.pdf.plugins/optimizer/
---
## فئة مُحسّن

تمثل إضافة `مُحسّن`.

```csharp
public sealed class Optimizer : IPlugin
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Optimizer](optimizer/)() | المُنشئ الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Process](../../aspose.pdf.plugins/optimizer/process/)(IPluginOptions) | يبدأ معالجة `مُحسّن` مع المعلمات المحددة. |

## الأمثلة

توضح المثال كيفية تحسين مستند PDF.

```csharp
// create Optimizer
var optimizer = new Optimizer();
// create OptimizeOptions object to set instructions
var opt = new OptimizeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
optimizer.Process(opt);
```

### انظر أيضًا

* واجهة [IPlugin](../iplugin/)
* مساحة الأسماء [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* التجميع [Aspose.PDF](../../)