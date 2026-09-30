---
title: "Html Class"
linktitle: "Html"
articleTitle: "Html"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.Html class. Represents Html plugin."
type: docs
weight: 390
url: "/net/aspose.pdf.lowcode/html/"
keywords: "Html, Aspose.Pdf.LowCode, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Html class

Represents [`Html`](../../aspose.pdf.lowcode/html/) plugin.

```csharp
public sealed class Html : IDisposable, IPlugin
```

## Examples

The example demonstrates how to convert PDF to HTML document.

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

The example demonstrates how to convert HTML to PDF document.

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

## Constructors

| Name | Description |
| --- | --- |
| [Html](./html/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](./dispose/)() | Implementation of IDisposable. |
| [Process](./process/)(IPluginOptions) | Starts the [`Html`](../../aspose.pdf.lowcode/html/) processing with the specified parameters. |

### See Also

* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)

