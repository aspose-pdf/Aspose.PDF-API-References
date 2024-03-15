---
title: Class PdfXls
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfXls class. Represents PdfXls plugin
type: docs
weight: 7010
url: /net/aspose.pdf.plugins/pdfxls/
---
## PdfXls class

Represents `PdfXls` plugin.

```csharp
public sealed class PdfXls : IDisposable, IPlugin
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfXls](pdfxls/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfxls/dispose/)() | Implementation of IDisposable. |
| [Process](../../aspose.pdf.plugins/pdfxls/process/)(IPluginOptions) | Starts the PdfToExcel processing with the specified parameters. |

## Examples

The example demonstrates how to convert PDF to XLSX document.

```csharp
// create PdfXLS converter
var converter = new PdfXLS();
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


