---
title: "Klass Optimizer"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Plugins.Optimizer-klass. Representerar Optimizer-plugin."
type: docs
weight: 9120
url: /sv/net/aspose.pdf.plugins/optimizer/
---
## Optimizer class

Representerar `Optimizer`-plugin.

```csharp
public sealed class Optimizer : IPlugin
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Optimizer](optimizer/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Process](../../aspose.pdf.plugins/optimizer/process/)(IPluginOptions) | Startar `Optimizer`-bearbetningen med de angivna parametrarna. |

## Exempel

Exemplet visar hur man optimerar PDF-dokument.

```csharp
// skapa Optimizer
var optimizer = new Optimizer();
// skapa OptimizeOptions-objekt för att ange instruktioner
var opt = new OptimizeOptions();
// lägg till indatafilvägar
opt.AddInput(new FileDataSource(inputPath));
// ange utdatafilens sökväg
opt.AddOutput(new FileDataSource(outputPath));
// utför processen
optimizer.Process(opt);
```

### Se även

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


