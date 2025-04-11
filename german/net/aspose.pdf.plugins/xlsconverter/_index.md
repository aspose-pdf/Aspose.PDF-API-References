---
title: Class XlsConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.XlsConverter-Klasse. Stellt das XlsConverter-Plugin dar
type: docs
weight: 9450
url: /de/net/aspose.pdf.plugins/xlsconverter/
---
## XlsConverter-Klasse

Stellt das `XlsConverter`-Plugin dar.

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [XlsConverter](xlsconverter/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | Implementierung von IDisposable. |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | Startet die PdfToExcel-Verarbeitung mit den angegebenen Parametern. |

## Beispiele

Das Beispiel zeigt, wie man ein PDF in ein XLSX-Dokument konvertiert.

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

### Siehe auch

* Schnittstelle [IPlugin](../iplugin/)
* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)