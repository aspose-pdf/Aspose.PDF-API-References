---
title: Class Merger
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.Merger. Rappresenta il plugin Merger
type: docs
weight: 8940
url: /it/net/aspose.pdf.plugins/merger/
---
## Classe Merger

Rappresenta il plugin `Merger`.

```csharp
public sealed class Merger : IPlugin
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Merger](merger/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Process](../../aspose.pdf.plugins/merger/process/)(IPluginOptions) | Avvia l'elaborazione del `Merger` con i parametri specificati. |

## Esempi

L'esempio dimostra come unire due documenti PDF.

```csharp
// create Merger
var merger = new Merger();
// create MergeOptions object to set instructions
var opt = new MergeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
merger.Process(opt);
```

### Vedi Anche

* interfaccia [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)