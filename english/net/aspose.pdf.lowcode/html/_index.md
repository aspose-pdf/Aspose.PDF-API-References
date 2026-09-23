---
title: Class Html
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LowCode.Html class. Represents Html plugin
type: docs
weight: 7440
url: /net/aspose.pdf.lowcode/html/
---
## Html class

Represents `Html` plugin.

```csharp
public sealed class Html : IDisposable, IPlugin
```

## Constructors

| Name | Description |
| --- | --- |
| [Html](html/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.lowcode/html/dispose/)() | Implementation of IDisposable. |
| [Process](../../aspose.pdf.lowcode/html/process/)(IPluginOptions) | Starts the `Html` processing with the specified parameters. |

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

### See Also

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)


