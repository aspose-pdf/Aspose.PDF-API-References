---
title: Class TableGenerator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.TableGenerator. Représente le plugin TableGenerator d'Aspose.PDF
type: docs
weight: 9350
url: /fr/net/aspose.pdf.plugins/tablegenerator/
---
## Classe TableGenerator

Représente le plugin TableGenerator d'Aspose.PDF.

```csharp
public sealed class TableGenerator : IDisposable, IPlugin
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TableGenerator](tablegenerator/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | Implémentation de IDisposable. En fait, ce n'est pas nécessaire pour TableGenerator. |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | Démarre le traitement de PdfGenerator avec les paramètres spécifiés. |

## Exemples

L'exemple démontre comment ajouter un tableau à un fichier PDF.

```csharp
// create TableGenerator
var generator = new TableGenerator();
// create TableOptions object to set instructions
var opt = new TableOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform extraction process
generator.Process(opt);
```

### Voir aussi

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)