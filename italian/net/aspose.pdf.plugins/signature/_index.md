---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.Signature. Rappresenta il plugin Firma
type: docs
weight: 9260
url: /it/net/aspose.pdf.plugins/signature/
---
## Classe Firma

Rappresenta il plugin `Signature`.

```csharp
public sealed class Signature : IPlugin
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Signature](signature/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | Avvia l'elaborazione `Signature` con i parametri specificati. |

## Esempi

L'esempio dimostra come firmare un documento PDF.

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

### Vedi Anche

* interfaccia [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)