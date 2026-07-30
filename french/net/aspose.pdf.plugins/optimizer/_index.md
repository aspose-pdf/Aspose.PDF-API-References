---
title: "Classe Optimizer"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Plugins.Optimizer. Représente le plugin Optimizer"
type: docs
weight: 9120
url: /fr/net/aspose.pdf.plugins/optimizer/
---
## Optimizer class

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

L'exemple montre comment optimiser le document PDF.

```csharp
// créer Optimizer
var optimizer = new Optimizer();
// créer un objet OptimizeOptions pour définir les instructions
var opt = new OptimizeOptions();
// ajouter les chemins des fichiers d'entrée
opt.AddInput(new FileDataSource(inputPath));
// définir le chemin du fichier de sortie
opt.AddOutput(new FileDataSource(outputPath));
// exécuter le processus
optimizer.Process(opt);
```

### Voir aussi

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


