---
title: Class Merger
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.Merger. Représente le plugin Merger
type: docs
weight: 8940
url: /fr/net/aspose.pdf.plugins/merger/
---
## Classe Merger

Représente le plugin `Merger`.

```csharp
public sealed class Merger : IPlugin
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Merger](merger/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Process](../../aspose.pdf.plugins/merger/process/)(IPluginOptions) | Démarre le traitement `Merger` avec les paramètres spécifiés. |

## Exemples

L'exemple démontre comment fusionner deux documents PDF.

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

### Voir aussi

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)