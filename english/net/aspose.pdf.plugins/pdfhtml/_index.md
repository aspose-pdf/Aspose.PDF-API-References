---
title: Class PdfHtml
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfHtml class. Represents PdfHtml plugin
type: docs
weight: 6720
url: /net/aspose.pdf.plugins/pdfhtml/
---
## PdfHtml class

Represents `PdfHtml` plugin.

```csharp
public sealed class PdfHtml : IDisposable, IPlugin
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfHtml](pdfhtml/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfhtml/dispose/)() | Implementation of IDisposable. |
| [Process](../../aspose.pdf.plugins/pdfhtml/process/)(IPluginOptions) | Starts the `PdfHtml` processing with the specified parameters. |

## Examples

The example demonstrates how to convert PDF to HTML document.

```csharp
// create PdfHtml
var converter = new PdfHtml();
// create PdfToHtmlOptions object to set output data type as file with embedded resources
var opt = new PdfToHtmlOptions(PdfToHtmlOptions.SaveDataType.FileWithEmbeddedResources);
// add input file path
opt.AddDataSource(new FileDataSource(inputPath));
// set output file path
opt.AddSaveDataSource(new FileDataSource(outputPath));
converter.Process(opt);
```

The example demonstrates how to convert HTML to PDF document.

```csharp
// create PdfHtml
var converter = new PdfHtml();
// create HtmlToPdfOptions
var opt = new HtmlToPdfOptions();
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


