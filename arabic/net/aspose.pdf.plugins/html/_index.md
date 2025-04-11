---
title: Class Html
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Plugins.Html. تمثل مكون Html
type: docs
weight: 8820
url: /ar/net/aspose.pdf.plugins/html/
---
## فئة Html

تمثل مكون `Html`.

```csharp
public sealed class Html : IDisposable, IPlugin
```

## البناة

| الاسم | الوصف |
| --- | --- |
| [Html](html/)() | الباني الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/html/dispose/)() | تنفيذ IDisposable. |
| [Process](../../aspose.pdf.plugins/html/process/)(IPluginOptions) | يبدأ معالجة `Html` مع المعلمات المحددة. |

## أمثلة

المثال يوضح كيفية تحويل PDF إلى مستند HTML.

```csharp
// create Html
var converter = new Html();
// create PdfToHtmlOptions object to set output data type as file with embedded resources
var opt = new PdfToHtmlOptions(PdfToHtmlOptions.SaveDataType.FileWithEmbeddedResources);
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

المثال يوضح كيفية تحويل HTML إلى مستند PDF.

```csharp
// create Html
var converter = new Html();
// create HtmlToPdfOptions
var opt = new HtmlToPdfOptions();
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### انظر أيضًا

* واجهة [IPlugin](../iplugin/)
* مساحة الأسماء [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* التجميع [Aspose.PDF](../../)