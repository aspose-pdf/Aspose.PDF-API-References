---
title: Class XlsConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.XlsConverter klass. Representerar XlsConverter-plugin
type: docs
weight: 9450
url: /sv/net/aspose.pdf.plugins/xlsconverter/
---
## XlsConverter klass

Representerar `XlsConverter`-plugin.

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [XlsConverter](xlsconverter/)() | Standardkonstruktören. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | Implementering av IDisposable. |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | Startar PdfToExcel-behandlingen med de angivna parametrarna. |

## Exempel

Exemplet visar hur man konverterar PDF till XLSX-dokument.

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

### Se Även

* gränssnitt [IPlugin](../iplugin/)
* namnrymd [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* samling [Aspose.PDF](../../)