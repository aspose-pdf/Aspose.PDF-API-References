---
title: Class XlsConverter
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Plugins.XlsConverter. تمثل مكون XlsConverter
type: docs
weight: 9450
url: /ar/net/aspose.pdf.plugins/xlsconverter/
---
## XlsConverter class

تمثل مكون `XlsConverter`.

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

## Constructors

| Name | Description |
| --- | --- |
| [XlsConverter](xlsconverter/)() | المُنشئ الافتراضي. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | تنفيذ IDisposable. |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | يبدأ معالجة PdfToExcel مع المعلمات المحددة. |

## Examples

توضح هذه المثال كيفية تحويل PDF إلى مستند XLSX.

```csharp
// create XlsConverter converter
var converter = new XlsConverter();
// create PdfToXLSOptions 
var opt = new PdfToXLSOptions();
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### See Also

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)