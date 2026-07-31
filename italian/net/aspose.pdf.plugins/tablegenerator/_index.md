---
title: "Classe TableGenerator"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Plugins.TableGenerator. Rappresenta il plugin Aspose.PDF TableGenerator"
type: docs
weight: 9500
url: /it/net/aspose.pdf.plugins/tablegenerator/
---
## TableGenerator class

Rappresenta il plugin Aspose.PDF TableGenerator.

```csharp
public sealed class TableGenerator : IDisposable, IPlugin
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TableGenerator](tablegenerator/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | Implementazione di IDisposable. In realtà, non è necessaria per TableGenerator. |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | Avvia l'elaborazione di PdfGenerator con i parametri specificati. |

## Esempi

L'esempio dimostra come aggiungere una tabella a un file PDF.

```csharp
// crea TableGenerator
var generator = new TableGenerator();
// crea l'oggetto TableOptions per impostare le istruzioni
var opt = new TableOptions();
// aggiungi i percorsi dei file di input
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// imposta il percorso del file di output
opt.AddOutput(new FileDataSource(outputPath));
// esegui il processo di estrazione
generator.Process(opt);
```

### Vedi anche

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


