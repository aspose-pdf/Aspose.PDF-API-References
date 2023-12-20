---
title: Class PdfExcel
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfExcel class. Represents PdfExcel plugin
type: docs
weight: 6530
url: /net/aspose.pdf.plugins/pdfexcel/
---
## PdfExcel class

Represents `PdfExcel` plugin.

```csharp
public sealed class PdfExcel : IDisposable, IPlugin
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfExcel](pdfexcel/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfexcel/dispose/)() | Implementation of IDisposable. |
| [Process](../../aspose.pdf.plugins/pdfexcel/process/)(IPluginOptions) | Starts the PdfToExcel processing with the specified parameters. |

## Examples

The example demonstrates how to convert PDF to XLSX document.

```csharp
// create PdfExcel converter
var converter = new PdfExcel();
// create PdfToExcelOptions 
var opt = new PdfToExcelOptions();
// add input file path
opt.AddDataSource(new FileDataSource(inputPath));
// set output file path
opt.AddSaveDataSource(new FileDataSource(outputPath));
converter.Process(opt);
```

### See Also

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


