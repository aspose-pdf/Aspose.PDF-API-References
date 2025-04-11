---
title: Class Splitter
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Plugins.Splitter. تمثل مكون قاطع
type: docs
weight: 9280
url: /ar/net/aspose.pdf.plugins/splitter/
---
## فئة قاطع

تمثل مكون `Splitter`.

```csharp
public class Splitter : IPlugin
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Splitter](splitter/)() | المنشئ الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Process](../../aspose.pdf.plugins/splitter/process/)(IPluginOptions) | يبدأ معالجة `Splitter` مع المعلمات المحددة. |

## أمثلة

توضح المثال كيفية تقسيم مستند PDF.

```csharp
// create Splitter
var splitter = new Splitter();
// create SplitOptions object to set instructions
var opt = new SplitOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file paths
opt.AddOutput(new FileDataSource(outputPath1));
opt.AddOutput(new FileDataSource(outputPath2));
// perform the process
splitter.Process(opt);
```

### انظر أيضًا

* واجهة [IPlugin](../iplugin/)
* مساحة الأسماء [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* التجميع [Aspose.PDF](../../)