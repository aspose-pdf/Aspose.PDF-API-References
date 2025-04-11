---
title: Class TocGenerator
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Plugins.TocGenerator. تمثل مكون Aspose.PDF TocGenerator
type: docs
weight: 9430
url: /ar/net/aspose.pdf.plugins/tocgenerator/
---
## TocGenerator class

تمثل مكون Aspose.PDF TocGenerator.

```csharp
public sealed class TocGenerator : IDisposable, IPlugin
```

## Constructors

| Name | Description |
| --- | --- |
| [TocGenerator](tocgenerator/)() | المُنشئ الافتراضي. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | تنفيذ IDisposable. في الواقع، ليس من الضروري لـ TocGenerator. |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | يبدأ معالجة PdfGenerator مع المعلمات المحددة. |

## Examples

المثال يوضح كيفية إضافة جدول المحتويات إلى ملف PDF.

```csharp
// create TocGenerator
var generator = new TocGenerator();
// create TocOptions object to set instructions
var opt = new TocOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform extraction process
generator.Process(opt);
```

### See Also

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)