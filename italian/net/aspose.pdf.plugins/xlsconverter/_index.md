---
title: "Classe XlsConverter"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Plugins.XlsConverter. Rappresenta il plugin XlsConverter"
type: docs
weight: 9600
url: /it/net/aspose.pdf.plugins/xlsconverter/
---
## XlsConverter class

Rappresenta il plugin `XlsConverter`.

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XlsConverter](xlsconverter/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | Implementazione di IDisposable. |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | Avvia l'elaborazione PdfToExcel con i parametri specificati. |

## Esempi

L'esempio dimostra come convertire PDF in documento XLSX.

```csharp
// crea convertitore XlsConverter
var converter = new XlsConverter();
// crea PdfToXLSOptions
var opt = new PdfToXLSOptions();
// aggiungi percorso del file di input
opt.AddInput(new FileDataSource(inputPath));
// imposta il percorso del file di output
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### Vedi anche

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


