---
title: Class Optimizer
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.Optimizer. Représente le plugin Optimizer
type: docs
weight: 8970
url: /fr/net/aspose.pdf.plugins/optimizer/
---
## Classe Optimizer

Représente le plugin `Optimizer`.

```csharp
public sealed class Optimizer : IPlugin
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Optimizer](optimizer/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Process](../../aspose.pdf.plugins/optimizer/process/)(IPluginOptions) | Démarre le traitement `Optimizer` avec les paramètres spécifiés. |

## Exemples

L'exemple démontre comment optimiser un document PDF.

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

### Voir aussi

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)