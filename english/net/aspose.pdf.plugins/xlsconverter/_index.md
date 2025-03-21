---
title: Class XlsConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.XlsConverter class. Represents XlsConverter plugin
type: docs
weight: 9450
url: /net/aspose.pdf.plugins/xlsconverter/
---
## XlsConverter class

Represents `XlsConverter` plugin.

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

## Constructors

| Name | Description |
| --- | --- |
| [XlsConverter](xlsconverter/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | Implementation of IDisposable. |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | Starts the PdfToExcel processing with the specified parameters. |

## Examples

The example demonstrates how to convert PDF to XLSX document.

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


