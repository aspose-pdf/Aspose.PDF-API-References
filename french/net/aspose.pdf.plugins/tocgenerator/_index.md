---
title: "Classe TocGenerator"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Plugins.TocGenerator. Représente le plug-in Aspose.PDF TocGenerator"
type: docs
weight: 9580
url: /fr/net/aspose.pdf.plugins/tocgenerator/
---
## TocGenerator class

Représente le plugin Aspose.PDF TocGenerator.

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
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | Implémentation de IDisposable. En fait, ce n'est pas nécessaire pour TocGenerator. |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | Démarre le traitement de PdfGenerator avec les paramètres spécifiés. |

## Exemples

L'exemple montre comment ajouter une table des matières (TOC) à un fichier PDF.

```csharp
// créer TocGenerator
var generator = new TocGenerator();
// créer un objet TocOptions pour définir les instructions
var opt = new TocOptions();
// ajouter les chemins des fichiers d'entrée
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// définir le chemin du fichier de sortie
opt.AddOutput(new FileDataSource(outputPath));
// exécuter le processus d'extraction
generator.Process(opt);
```

### Voir aussi

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


