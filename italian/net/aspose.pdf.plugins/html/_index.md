---
title: "Classe Html"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Plugins.Html. Rappresenta il plugin Html."
type: docs
weight: 8950
url: /it/net/aspose.pdf.plugins/html/
---
## Html class

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

L'esempio dimostra come convertire un documento PDF in HTML.

```csharp
// crea Html
var converter = new Html();
// crea l'oggetto PdfToHtmlOptions per impostare il tipo di dati di output come file con risorse incorporate.
var opt = new PdfToHtmlOptions(PdfToHtmlOptions.SaveDataType.FileWithEmbeddedResources);
// aggiungi percorso del file di input
opt.AddInput(new FileDataSource(inputPath));
// imposta il percorso del file di output
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

L'esempio dimostra come convertire un documento HTML in PDF.

```csharp
// crea Html
var converter = new Html();
// crea HtmlToPdfOptions
var opt = new HtmlToPdfOptions();
// aggiungi percorso del file di input
opt.AddInput(new FileDataSource(inputPath));
// imposta il percorso del file di output
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### Vedi anche

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


