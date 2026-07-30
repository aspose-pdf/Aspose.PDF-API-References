---
title: "Classe Html"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Plugins.Html classe. Représente le plugin Html"
type: docs
weight: 8950
url: /fr/net/aspose.pdf.plugins/html/
---
## Html class

Représente le plugin `Html`.

```csharp
public sealed class Html : IDisposable, IPlugin
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Html](html/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/html/dispose/)() | Implémentation de IDisposable. |
| [Process](../../aspose.pdf.plugins/html/process/)(IPluginOptions) | Démarre le traitement `Html` avec les paramètres spécifiés. |

## Exemples

L'exemple montre comment convertir un PDF en document HTML.

```csharp
// créer Html
var converter = new Html();
// créer un objet PdfToHtmlOptions pour définir le type de données de sortie comme fichier avec des ressources intégrées
var opt = new PdfToHtmlOptions(PdfToHtmlOptions.SaveDataType.FileWithEmbeddedResources);
// ajouter le chemin du fichier d'entrée
opt.AddInput(new FileDataSource(inputPath));
// définir le chemin du fichier de sortie
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

L'exemple montre comment convertir un document HTML en PDF.

```csharp
// créer Html
var converter = new Html();
// créer HtmlToPdfOptions
var opt = new HtmlToPdfOptions();
// ajouter le chemin du fichier d'entrée
opt.AddInput(new FileDataSource(inputPath));
// définir le chemin du fichier de sortie
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### Voir aussi

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


