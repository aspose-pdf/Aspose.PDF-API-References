---
title: Class XlsConverter
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.XlsConverter. Rappresenta il plugin XlsConverter
type: docs
weight: 9450
url: /it/net/aspose.pdf.plugins/xlsconverter/
---
## Classe XlsConverter

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

L'esempio dimostra come convertire un documento PDF in XLSX.

```csharp
// create XlsConverter converter
var converter = new XlsConverter();
// create PdfToXLSOptions 
var opt = new PdfToXLSOptions();
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### Vedi Anche

* interfaccia [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)