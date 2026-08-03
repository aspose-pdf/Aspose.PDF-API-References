---
title: "Klass Merger"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Plugins.Merger-klass. Representerar Merger‑plugin"
type: docs
weight: 9070
url: /sv/net/aspose.pdf.plugins/merger/
---
## Merger class

Representerar `Merger`‑plugin.

```csharp
public sealed class Merger : IPlugin
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Merger](merger/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Process](../../aspose.pdf.plugins/merger/process/)(IPluginOptions) | Startar `Merger`‑processen med de angivna parametrarna. |

## Exempel

Exemplet visar hur man slår ihop två PDF-dokument.

```csharp
// skapa Merger
var merger = new Merger();
// skapa MergeOptions‑objekt för att ange instruktioner
var opt = new MergeOptions();
// lägg till indatafilvägar
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// ange utdatafilens sökväg
opt.AddOutput(new FileDataSource(outputPath));
// utför processen
merger.Process(opt);
```

### Se även

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


