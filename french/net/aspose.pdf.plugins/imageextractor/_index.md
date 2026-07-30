---
title: "Classe ImageExtractor"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Plugins.ImageExtractor. Représente le plugin ImageExtractor"
type: docs
weight: 9020
url: /fr/net/aspose.pdf.plugins/imageextractor/
---
## ImageExtractor class

Représente le plugin ImageExtractor.

```csharp
public class ImageExtractor : PdfExtractor
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ImageExtractor](imageextractor/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implémentation de IDisposable. En fait, ce n'est pas nécessaire pour PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Démarre le traitement PdfExtractor avec les paramètres spécifiés. |

## Remarques

L'objet `ImageExtractor` est utilisé pour extraire du texte dans les documents PDF.

## Exemples

L'exemple montre comment extraire des images d'un document PDF.

```csharp
// créez un objet ImageExtractor pour extraire des images
using (ImageExtractor extractor = new ImageExtractor())
{
    // créez ImageExtractorOptions
    imageExtractorOptions = new ImageExtractorOptions();
    
    // ajoutez le chemin du fichier d'entrée aux sources de données
    imageExtractor.AddDataSource(new FileDataSource(inputPath));
    
    // exécuter le processus d'extraction
    ResultContainer resultContainer = extractor.Process(imageExtractorOptions);
    
    // obtenez l'image à partir de l'objet ResultContainer
    var imageExtracted = resultContainer.ResultCollection[0].ToFile();
}
```

### Voir aussi

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


