---
title: "XlsConverter Class"
linktitle: "XlsConverter"
articleTitle: "XlsConverter"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.XlsConverter class. Represents XlsConverter plugin."
type: docs
weight: 1060
url: "/net/aspose.pdf.lowcode/xlsconverter/"
keywords: "XlsConverter, Aspose.Pdf.LowCode, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## XlsConverter class

Represents [`XlsConverter`](../../aspose.pdf.lowcode/xlsconverter/) plugin.

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

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

## Constructors

| Name | Description |
| --- | --- |
| [XlsConverter](./xlsconverter/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](./dispose/)() | Implementation of IDisposable. |
| [Process](./process/)(IPluginOptions) | Starts the PdfToExcel processing with the specified parameters. |

### See Also

* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)

