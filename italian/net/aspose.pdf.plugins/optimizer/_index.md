---
title: Class Optimizer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Optimizzatore classe. Rappresenta Optimizzatore plugin
type: docs
weight: 8970
url: /it/net/aspose.pdf.plugins/optimizer/
---
## Classe Ottimizzatore

Rappresenta il plugin `Optimizer`.

```csharp
public sealed class Optimizer : IPlugin
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Optimizer](optimizer/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Process](../../aspose.pdf.plugins/optimizer/process/)(IPluginOptions) | Avvia l'elaborazione `Optimizer` con i parametri specificati. |

## Esempi

L'esempio dimostra come ottimizzare un documento PDF.

```csharp
// create Optimizer
var optimizer = new Optimizer();
// create OptimizeOptions object to set instructions
var opt = new OptimizeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
optimizer.Process(opt);
```

### Vedi Anche

* interfaccia [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)