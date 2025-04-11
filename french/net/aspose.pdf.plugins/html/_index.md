---
title: Class Html
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.Html. Représente le plugin Html
type: docs
weight: 8820
url: /fr/net/aspose.pdf.plugins/html/
---
## Classe Html

Représente le plugin `Html`.

```csharp
public sealed class Html : IDisposable, IPlugin
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Html](html/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/html/dispose/)() | Implémentation de IDisposable. |
| [Process](../../aspose.pdf.plugins/html/process/)(IPluginOptions) | Démarre le traitement `Html` avec les paramètres spécifiés. |

## Exemples

L'exemple démontre comment convertir un PDF en document HTML.

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

L'exemple démontre comment convertir un document HTML en PDF.

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

### Voir aussi

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)