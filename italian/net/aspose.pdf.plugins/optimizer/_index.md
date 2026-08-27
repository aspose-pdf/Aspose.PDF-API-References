---
title: "Classe Optimizer"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Plugins.Optimizer. Rappresenta il plugin Optimizer"
type: docs
weight: 9120
url: /it/net/aspose.pdf.plugins/optimizer/
---
## Optimizer class

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
// crea Optimizer
var optimizer = new Optimizer();
// crea l'oggetto OptimizeOptions per impostare le istruzioni
var opt = new OptimizeOptions();
// aggiungi i percorsi dei file di input
opt.AddInput(new FileDataSource(inputPath));
// imposta il percorso del file di output
opt.AddOutput(new FileDataSource(outputPath));
// esegui il processo
optimizer.Process(opt);
```

### Vedi anche

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


