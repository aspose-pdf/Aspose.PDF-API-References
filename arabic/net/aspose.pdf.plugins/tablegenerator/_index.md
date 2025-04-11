---
title: Class TableGenerator
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Plugins.TableGenerator. تمثل مكون Aspose.PDF TableGenerator
type: docs
weight: 9350
url: /ar/net/aspose.pdf.plugins/tablegenerator/
---
## TableGenerator class

تمثل مكون Aspose.PDF TableGenerator.

```csharp
public sealed class TableGenerator : IDisposable, IPlugin
```

## Constructors

| Name | Description |
| --- | --- |
| [TableGenerator](tablegenerator/)() | المُنشئ الافتراضي. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | تنفيذ IDisposable. في الواقع، ليس من الضروري لمكون TableGenerator. |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | يبدأ معالجة PdfGenerator مع المعلمات المحددة. |

## Examples

توضح المثال كيفية إضافة جدول إلى ملف PDF.

```csharp
// create TableGenerator
var generator = new TableGenerator();
// create TableOptions object to set instructions
var opt = new TableOptions();
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