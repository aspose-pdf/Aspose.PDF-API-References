---
title: Class TocGenerator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.TocGenerator. Représente le plugin TocGenerator d'Aspose.PDF
type: docs
weight: 9430
url: /fr/net/aspose.pdf.plugins/tocgenerator/
---
## Classe TocGenerator

Représente le plugin TocGenerator d'Aspose.PDF.

```csharp
public sealed class TocGenerator : IDisposable, IPlugin
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TocGenerator](tocgenerator/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | Mise en œuvre de IDisposable. En fait, ce n'est pas nécessaire pour TocGenerator. |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | Démarre le traitement de PdfGenerator avec les paramètres spécifiés. |

## Exemples

L'exemple démontre comment ajouter une table des matières à un fichier PDF.

```csharp
// create TocGenerator
var generator = new TocGenerator();
// create TocOptions object to set instructions
var opt = new TocOptions();
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