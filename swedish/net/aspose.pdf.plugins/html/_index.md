---
title: Class Html
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Html klass. Representerar Html-plugin
type: docs
weight: 8820
url: /sv/net/aspose.pdf.plugins/html/
---
## Html klass

Representerar `Html` plugin.

```csharp
public sealed class Html : IDisposable, IPlugin
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Html](html/)() | Standardkonstruktören. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/html/dispose/)() | Implementering av IDisposable. |
| [Process](../../aspose.pdf.plugins/html/process/)(IPluginOptions) | Startar `Html` bearbetning med angivna parametrar. |

## Exempel

Exemplet visar hur man konverterar PDF till HTML-dokument.

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

Exemplet visar hur man konverterar HTML till PDF-dokument.

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

### Se Även

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)