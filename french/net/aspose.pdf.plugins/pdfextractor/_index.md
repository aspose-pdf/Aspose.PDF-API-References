---
title: "Classe PdfExtractor"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Plugins.PdfExtractor. Représente la fonctionnalité de base pour extraire du texte, des images et d’autres types de contenu pouvant apparaître sur les pages de documents PDF."
type: docs
weight: 9210
url: /fr/net/aspose.pdf.plugins/pdfextractor/
---
## PdfExtractor class

Représente la fonctionnalité de base pour extraire du texte, des images et d'autres types de contenu pouvant apparaître sur les pages de documents PDF.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implémentation de IDisposable. En fait, ce n'est pas nécessaire pour PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Démarre le traitement PdfExtractor avec les paramètres spécifiés. |

## Remarques

L’objet [`TextExtractor`](../textextractor/) est utilisé pour extraire du texte, ou [`ImageExtractor`](../imageextractor/) pour extraire des images.

## Exemples

L'exemple montre comment extraire le contenu texte d'un document PDF.

```csharp
// créez un objet TextExtractor pour extraire le contenu PDF.
using (TextExtractor extractor = new TextExtractor())
{
    // créez l’objet TextExtractorOptions pour définir les instructions
    textExtractorOptions = new TextExtractorOptions();
    
    // ajoutez le chemin du fichier d'entrée aux sources de données
    textExtractorOptions.AddInput(new FileDataSource(inputPath));
    
    // exécuter le processus d'extraction
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // obtenez le texte extrait depuis l'objet ResultContainer
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Voir aussi

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


