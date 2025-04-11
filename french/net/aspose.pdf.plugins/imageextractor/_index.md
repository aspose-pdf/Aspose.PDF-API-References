---
title: Class ImageExtractor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.ImageExtractor. Représente le plugin ImageExtractor
type: docs
weight: 8890
url: /fr/net/aspose.pdf.plugins/imageextractor/
---
## Classe ImageExtractor

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
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Démarre le traitement de PdfExtractor avec les paramètres spécifiés. |

## Remarques

L'objet `ImageExtractor` est utilisé pour extraire du texte dans des documents PDF.

## Exemples

L'exemple démontre comment extraire des images d'un document PDF.

```csharp
// create ImageExtractor object to extract images
using (ImageExtractor extractor = new ImageExtractor())
{
    // create ImageExtractorOptions
    imageExtractorOptions = new ImageExtractorOptions();
    
    // add input file path to data sources
    imageExtractor.AddDataSource(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(imageExtractorOptions);
    
    // get the image from the ResultContainer object
    var imageExtracted = resultContainer.ResultCollection[0].ToFile();
}
```

### Voir aussi

* classe [PdfExtractor](../pdfextractor/)
* espace de noms [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)