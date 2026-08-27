---
title: "Klass XlsConverter"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Plugins.XlsConverter‑klass. Representerar XlsConverter‑plugin"
type: docs
weight: 9600
url: /sv/net/aspose.pdf.plugins/xlsconverter/
---
## XlsConverter class

Representerar `XlsConverter`‑plugin.

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [XlsConverter](xlsconverter/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | Implementering av IDisposable. |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | Startar PdfToExcel‑bearbetning med de angivna parametrarna. |

## Exempel

Exemplet visar hur man konverterar PDF till XLSX‑dokument.

```csharp
// skapa XlsConverter‑konverterare
var converter = new XlsConverter();
// skapa PdfToXLSOptions
var opt = new PdfToXLSOptions();
// lägg till indatafilens sökväg
opt.AddInput(new FileDataSource(inputPath));
// ange utdatafilens sökväg
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### Se även

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


