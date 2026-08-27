---
title: "Classe Splitter"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Plugins.Splitter class. Représente le plugin Splitter"
type: docs
weight: 9430
url: /fr/net/aspose.pdf.plugins/splitter/
---
## Splitter class

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

L'exemple montre comment diviser un document PDF.

```csharp
// créer Splitter
var splitter = new Splitter();
// créer un objet SplitOptions pour définir les instructions
var opt = new SplitOptions();
// ajouter les chemins des fichiers d'entrée
opt.AddInput(new FileDataSource(inputPath));
// définir les chemins de fichiers de sortie
opt.AddOutput(new FileDataSource(outputPath1));
opt.AddOutput(new FileDataSource(outputPath2));
// exécuter le processus
splitter.Process(opt);
```

### Voir aussi

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


