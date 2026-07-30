---
title: "Classe TableGenerator"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Plugins.TableGenerator. Représente le plugin Aspose.PDF TableGenerator"
type: docs
weight: 9500
url: /fr/net/aspose.pdf.plugins/tablegenerator/
---
## TableGenerator class

Représente le plugin Aspose.PDF TableGenerator.

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

L'exemple montre comment ajouter un tableau à un fichier PDF.

```csharp
// créer TableGenerator
var generator = new TableGenerator();
// créer un objet TableOptions pour définir les instructions
var opt = new TableOptions();
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


