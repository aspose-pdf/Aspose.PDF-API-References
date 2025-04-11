---
title: Class TocGenerator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.TocGenerator. Rappresenta il plugin TocGenerator di Aspose.PDF
type: docs
weight: 9430
url: /it/net/aspose.pdf.plugins/tocgenerator/
---
## Classe TocGenerator

Rappresenta il plugin TocGenerator di Aspose.PDF.

```csharp
public sealed class TocGenerator : IDisposable, IPlugin
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TocGenerator](tocgenerator/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | Implementazione di IDisposable. In effetti, non è necessario per TocGenerator. |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | Avvia l'elaborazione di PdfGenerator con i parametri specificati. |

## Esempi

L'esempio dimostra come aggiungere un TOC a un file PDF.

```csharp
// create TocGenerator
var generator = new TocGenerator();
// create TocOptions object to set instructions
var opt = new TocOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform extraction process
generator.Process(opt);
```

### Vedi Anche

* interfaccia [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)