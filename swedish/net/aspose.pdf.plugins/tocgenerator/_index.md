---
title: Class TocGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TocGenerator klass. Representerar Aspose.PDF TocGenerator-plugin
type: docs
weight: 9430
url: /sv/net/aspose.pdf.plugins/tocgenerator/
---
## TocGenerator klass

Representerar Aspose.PDF TocGenerator-plugin.

```csharp
public sealed class TocGenerator : IDisposable, IPlugin
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TocGenerator](tocgenerator/)() | Standardkonstruktören. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | Implementering av IDisposable. Faktum är att det inte är nödvändigt för TocGenerator. |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | Startar PdfGenerator-behandlingen med de angivna parametrarna. |

## Exempel

Exemplet visar hur man lägger till TOC i PDF-fil.

```csharp
// create TocGenerator
var generator = new TocGenerator();
// create TocOptions object to set instructions
var opt = new TocOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform extraction process
generator.Process(opt);
```

### Se Även

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)