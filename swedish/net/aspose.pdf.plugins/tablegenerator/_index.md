---
title: "Klass TableGenerator"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Plugins.TableGenerator-klass. Representerar Aspose.PDF TableGenerator-plugin."
type: docs
weight: 9500
url: /sv/net/aspose.pdf.plugins/tablegenerator/
---
## TableGenerator class

Representerar Aspose.PDF TableGenerator‑plugin.

```csharp
public sealed class TableGenerator : IDisposable, IPlugin
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TableGenerator](tablegenerator/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | Implementering av IDisposable. Faktum är att det inte är nödvändigt för TableGenerator. |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | Startar PdfGenerator-bearbetningen med de angivna parametrarna. |

## Exempel

Exemplet visar hur man lägger till en tabell i PDF-filen.

```csharp
// skapa TableGenerator
var generator = new TableGenerator();
// skapa TableOptions-objekt för att ange instruktioner
var opt = new TableOptions();
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


