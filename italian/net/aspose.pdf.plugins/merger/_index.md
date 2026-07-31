---
title: "Classe Merger"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Plugins.Merger classe. Rappresenta il plugin Merger"
type: docs
weight: 9070
url: /it/net/aspose.pdf.plugins/merger/
---
## Merger class

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
| [Process](../../aspose.pdf.plugins/merger/process/)(IPluginOptions) | Avvia l'elaborazione `Merger` con i parametri specificati. |

## Esempi

L'esempio dimostra come unire due documenti PDF.

```csharp
// crea Merger
var merger = new Merger();
// crea l'oggetto MergeOptions per impostare le istruzioni
var opt = new MergeOptions();
// aggiungi i percorsi dei file di input
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// imposta il percorso del file di output
opt.AddOutput(new FileDataSource(outputPath));
// esegui il processo
merger.Process(opt);
```

### Vedi anche

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


