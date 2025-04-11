---
title: Class Optimizer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Optimizer klass. Representerar Optimizer-plugin
type: docs
weight: 8970
url: /sv/net/aspose.pdf.plugins/optimizer/
---
## Optimizer klass

Representerar `Optimizer` plugin.

```csharp
public sealed class Optimizer : IPlugin
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Optimizer](optimizer/)() | Standardkonstruktören. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Process](../../aspose.pdf.plugins/optimizer/process/)(IPluginOptions) | Startar `Optimizer` bearbetning med angivna parametrar. |

## Exempel

Exemplet visar hur man optimerar en PDF-dokument.

```csharp
// create Optimizer
var optimizer = new Optimizer();
// create OptimizeOptions object to set instructions
var opt = new OptimizeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
optimizer.Process(opt);
```

### Se Även

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)