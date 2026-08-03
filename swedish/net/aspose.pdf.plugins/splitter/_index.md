---
title: "Klass Splitter"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Plugins.Splitter-klass. Representerar Splitter‑plugin"
type: docs
weight: 9430
url: /sv/net/aspose.pdf.plugins/splitter/
---
## Splitter class

Representerar `Splitter`‑plugin.

```csharp
public class Splitter : IPlugin
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Splitter](splitter/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Process](../../aspose.pdf.plugins/splitter/process/)(IPluginOptions) | Startar `Splitter`‑bearbetningen med de angivna parametrarna. |

## Exempel

Exemplet visar hur man delar PDF-dokumentet.

```csharp
// skapa Splitter
var splitter = new Splitter();
// skapa SplitOptions-objekt för att ange instruktioner
var opt = new SplitOptions();
// lägg till indatafilvägar
opt.AddInput(new FileDataSource(inputPath));
// ange sökvägar för utdatafiler
opt.AddOutput(new FileDataSource(outputPath1));
opt.AddOutput(new FileDataSource(outputPath2));
// utför processen
splitter.Process(opt);
```

### Se även

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


