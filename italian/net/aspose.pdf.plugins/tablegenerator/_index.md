---
title: Class TableGenerator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.TableGenerator. Rappresenta il plugin TableGenerator di Aspose.PDF
type: docs
weight: 9350
url: /it/net/aspose.pdf.plugins/tablegenerator/
---
## Classe TableGenerator

Rappresenta il plugin TableGenerator di Aspose.PDF.

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
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | Implementazione di IDisposable. In effetti, non è necessario per TableGenerator. |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | Avvia l'elaborazione di PdfGenerator con i parametri specificati. |

## Esempi

L'esempio dimostra come aggiungere una tabella a un file PDF.

```csharp
// create TableGenerator
var generator = new TableGenerator();
// create TableOptions object to set instructions
var opt = new TableOptions();
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