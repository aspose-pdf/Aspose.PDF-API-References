---
title: "Klass TocGenerator"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Plugins.TocGenerator-klass. Representerar Aspose.PDF TocGenerator-plugin."
type: docs
weight: 9580
url: /sv/net/aspose.pdf.plugins/tocgenerator/
---
## TocGenerator class

Representerar Aspose.PDF TocGenerator‑plugin.

```csharp
public sealed class TocGenerator : IDisposable, IPlugin
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TocGenerator](tocgenerator/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | Implementering av IDisposable. Faktum är att det inte är nödvändigt för TocGenerator. |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | Startar PdfGenerator-bearbetningen med de angivna parametrarna. |

## Exempel

Exemplet visar hur man lägger till TOC i en PDF-fil.

```csharp
// skapa TocGenerator
var generator = new TocGenerator();
// skapa TocOptions-objekt för att ange instruktioner
var opt = new TocOptions();
// lägg till indatafilvägar
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// ange utdatafilens sökväg
opt.AddOutput(new FileDataSource(outputPath));
// utför extraktionsprocessen
generator.Process(opt);
```

### Se även

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


