---
title: Class Merger
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Sammanfogning klass. Representerar Sammanfogning plugin
type: docs
weight: 8940
url: /sv/net/aspose.pdf.plugins/merger/
---
## Sammanfogning klass

Representerar `Sammanfogning` plugin.

```csharp
public sealed class Merger : IPlugin
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Sammanfogning](sammanfogning/)() | Standardkonstruktören. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Bearbeta](../../aspose.pdf.plugins/sammanfogning/bearbeta/)(IPluginOptions) | Startar `Sammanfogning` bearbetning med angivna parametrar. |

## Exempel

Exemplet visar hur man sammanfogar två PDF-dokument.

```csharp
// create Merger
var merger = new Merger();
// create MergeOptions object to set instructions
var opt = new MergeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
merger.Process(opt);
```

### Se Även

* gränssnitt [IPlugin](../iplugin/)
* namnrymd [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* samling [Aspose.PDF](../../)