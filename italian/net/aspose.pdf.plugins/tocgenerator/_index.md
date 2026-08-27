---
title: "Classe TocGenerator"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Plugins.TocGenerator classe. Rappresenta il plugin Aspose.PDF TocGenerator"
type: docs
weight: 9580
url: /it/net/aspose.pdf.plugins/tocgenerator/
---
## TocGenerator class

Rappresenta il plugin Aspose.PDF TocGenerator.

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
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | Implementazione di IDisposable. In realtà, non è necessaria per TocGenerator. |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | Avvia l'elaborazione di PdfGenerator con i parametri specificati. |

## Esempi

L'esempio dimostra come aggiungere il TOC al file PDF.

```csharp
// crea TocGenerator
var generator = new TocGenerator();
// crea l'oggetto TocOptions per impostare le istruzioni
var opt = new TocOptions();
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


