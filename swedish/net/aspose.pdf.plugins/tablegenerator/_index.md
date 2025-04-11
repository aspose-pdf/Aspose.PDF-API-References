---
title: Class TableGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TableGenerator klass. Representerar Aspose.PDF TableGenerator-plugin
type: docs
weight: 9350
url: /sv/net/aspose.pdf.plugins/tablegenerator/
---
## TableGenerator klass

Representerar Aspose.PDF TableGenerator-plugin.

```csharp
public sealed class TableGenerator : IDisposable, IPlugin
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TableGenerator](tablegenerator/)() | Standardkonstruktören. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | Implementering av IDisposable. Faktum är att det inte är nödvändigt för TableGenerator. |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | Startar PdfGenerator-behandlingen med de angivna parametrarna. |

## Exempel

Exemplet visar hur man lägger till en tabell i PDF-filen.

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

### Se Även

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)