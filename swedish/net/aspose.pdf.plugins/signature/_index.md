---
title: "Klassen Signature"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Plugins.Signature-klass. Representerar Signature‑plugin"
type: docs
weight: 9410
url: /sv/net/aspose.pdf.plugins/signature/
---
## Signature class

Representerar `Signature`‑plugin.

```csharp
public sealed class Signature : IPlugin
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Signature](signature/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | Startar `Signature`‑bearbetningen med de angivna parametrarna. |

## Exempel

Exemplet visar hur man signerar PDF‑dokument.

```csharp
// skapa Signature
var plugin = new Signature();
// skapa SignOptions‑objekt för att ange instruktioner
var opt = new SignOptions(inputPfx, inputPfxPassword);
// lägg till indatafilens sökväg
opt.AddInput(new FileDataSource(inputPath));
// ange utdatafilens sökväg
opt.AddOutput(new FileDataSource(outputPath));
// utför processen
plugin.Process(opt);
```

### Se även

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


