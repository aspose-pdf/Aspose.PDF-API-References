---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.Signature. Représente le plugin Signature
type: docs
weight: 9260
url: /fr/net/aspose.pdf.plugins/signature/
---
## Classe Signature

Représente le plugin `Signature`.

```csharp
public sealed class Signature : IPlugin
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Signature](signature/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | Démarre le traitement `Signature` avec les paramètres spécifiés. |

## Exemples

L'exemple démontre comment signer un document PDF.

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

### Voir aussi

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)