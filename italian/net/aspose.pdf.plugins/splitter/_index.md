---
title: "Classe Splitter"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Plugins.Splitter class. Rappresenta il plugin Splitter"
type: docs
weight: 9430
url: /it/net/aspose.pdf.plugins/splitter/
---
## Splitter class

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

L'esempio dimostra come dividere un documento PDF.

```csharp
// crea Splitter
var splitter = new Splitter();
// crea l'oggetto SplitOptions per impostare le istruzioni
var opt = new SplitOptions();
// aggiungi i percorsi dei file di input
opt.AddInput(new FileDataSource(inputPath));
// imposta i percorsi dei file di output
opt.AddOutput(new FileDataSource(outputPath1));
opt.AddOutput(new FileDataSource(outputPath2));
// esegui il processo
splitter.Process(opt);
```

### Vedi anche

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


