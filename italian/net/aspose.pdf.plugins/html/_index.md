---
title: Class Html
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.Html. Rappresenta il plugin Html
type: docs
weight: 8820
url: /it/net/aspose.pdf.plugins/html/
---
## Classe Html

Rappresenta il plugin `Html`.

```csharp
public sealed class Html : IDisposable, IPlugin
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Html](html/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/html/dispose/)() | Implementazione di IDisposable. |
| [Process](../../aspose.pdf.plugins/html/process/)(IPluginOptions) | Avvia l'elaborazione `Html` con i parametri specificati. |

## Esempi

L'esempio dimostra come convertire un PDF in un documento HTML.

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

L'esempio dimostra come convertire un documento HTML in PDF.

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

### Vedi Anche

* interfaccia [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)