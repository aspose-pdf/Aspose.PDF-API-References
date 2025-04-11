---
title: Class Splitter
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.Splitter. Rappresenta il plugin Splitter
type: docs
weight: 9280
url: /it/net/aspose.pdf.plugins/splitter/
---
## Classe Splitter

Rappresenta il plugin `Splitter`.

```csharp
public class Splitter : IPlugin
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Splitter](splitter/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Process](../../aspose.pdf.plugins/splitter/process/)(IPluginOptions) | Avvia l'elaborazione del `Splitter` con i parametri specificati. |

## Esempi

L'esempio dimostra come suddividere un documento PDF.

```csharp
// create Splitter
var splitter = new Splitter();
// create SplitOptions object to set instructions
var opt = new SplitOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file paths
opt.AddOutput(new FileDataSource(outputPath1));
opt.AddOutput(new FileDataSource(outputPath2));
// perform the process
splitter.Process(opt);
```

### Vedi Anche

* interfaccia [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)