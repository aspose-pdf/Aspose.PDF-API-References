---
title: Class XlsConverter
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.XlsConverter. Représente le plugin XlsConverter
type: docs
weight: 9450
url: /fr/net/aspose.pdf.plugins/xlsconverter/
---
## Classe XlsConverter

Représente le plugin `XlsConverter`.

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [XlsConverter](xlsconverter/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | Implémentation de IDisposable. |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | Démarre le traitement PdfToExcel avec les paramètres spécifiés. |

## Exemples

L'exemple démontre comment convertir un document PDF en document XLSX.

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

### Voir aussi

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)