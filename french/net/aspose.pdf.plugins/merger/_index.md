---
title: "Classe Merger"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Plugins.Merger. Représente le plugin Merger"
type: docs
weight: 9070
url: /fr/net/aspose.pdf.plugins/merger/
---
## Merger class

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

L'exemple montre comment fusionner deux documents PDF.

```csharp
// créer Merger
var merger = new Merger();
// créer l'objet MergeOptions pour définir les instructions
var opt = new MergeOptions();
// ajouter les chemins des fichiers d'entrée
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// définir le chemin du fichier de sortie
opt.AddOutput(new FileDataSource(outputPath));
// exécuter le processus
merger.Process(opt);
```

### Voir aussi

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


