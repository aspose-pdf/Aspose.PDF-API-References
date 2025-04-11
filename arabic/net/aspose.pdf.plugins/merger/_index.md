---
title: Class Merger
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Plugins.Merger. تمثل مكون الدمج
type: docs
weight: 8940
url: /ar/net/aspose.pdf.plugins/merger/
---
## فئة الدمج

تمثل مكون `Merger`.

```csharp
public sealed class Merger : IPlugin
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Merger](merger/)() | المنشئ الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Process](../../aspose.pdf.plugins/merger/process/)(IPluginOptions) | يبدأ معالجة `Merger` مع المعلمات المحددة. |

## أمثلة

توضح المثال كيفية دمج مستندين PDF.

```csharp
// create Merger
var merger = new Merger();
// create MergeOptions object to set instructions
var opt = new MergeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
merger.Process(opt);
```

### انظر أيضًا

* واجهة [IPlugin](../iplugin/)
* مساحة الأسماء [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* التجميع [Aspose.PDF](../../)