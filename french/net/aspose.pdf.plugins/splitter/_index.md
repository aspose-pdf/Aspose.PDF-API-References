---
title: Class Splitter
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.Splitter. Représente le plugin Splitter
type: docs
weight: 9280
url: /fr/net/aspose.pdf.plugins/splitter/
---
## Classe Splitter

Représente le plugin `Splitter`.

```csharp
public class Splitter : IPlugin
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Splitter](splitter/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Process](../../aspose.pdf.plugins/splitter/process/)(IPluginOptions) | Démarre le traitement `Splitter` avec les paramètres spécifiés. |

## Exemples

L'exemple démontre comment diviser un document PDF.

```csharp
// create Splitter
var splitter = new Splitter();
// create SplitOptions object to set instructions
var opt = new SplitOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file paths
opt.AddOutput(new FileDataSource(outputPath1));
opt.AddOutput(new FileDataSource(outputPath2));
// perform the process
splitter.Process(opt);
```

### Voir aussi

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)