---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Signature klass. Representerar Signature-plugin
type: docs
weight: 9260
url: /sv/net/aspose.pdf.plugins/signature/
---
## Signatur klass

Representerar `Signature` plugin.

```csharp
public sealed class Signature : IPlugin
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Signature](signature/)() | Standardkonstruktören. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | Startar `Signature` bearbetning med angivna parametrar. |

## Exempel

Exemplet visar hur man signerar en PDF-dokument.

```csharp
// create Signature
var plugin = new Signature();
// create SignOptions object to set instructions
var opt = new SignOptions(inputPfx, inputPfxPassword);
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

### Se Även

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)