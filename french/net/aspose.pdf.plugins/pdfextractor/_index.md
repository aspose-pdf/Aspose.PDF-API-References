---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.PdfExtractor. Représente la fonctionnalité de base pour extraire du texte, des images et d'autres types de contenu qui peuvent apparaître sur les pages des documents PDF
type: docs
weight: 9060
url: /fr/net/aspose.pdf.plugins/pdfextractor/
---
## Classe PdfExtractor

Représente la fonctionnalité de base pour extraire du texte, des images et d'autres types de contenu qui peuvent apparaître sur les pages des documents PDF.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implémentation de IDisposable. En réalité, ce n'est pas nécessaire pour PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Démarre le traitement de PdfExtractor avec les paramètres spécifiés. |

## Remarques

L'objet [`TextExtractor`](../textextractor/) est utilisé pour extraire du texte, ou [`ImageExtractor`](../imageextractor/) pour extraire des images.

## Exemples

L'exemple démontre comment extraire le contenu textuel d'un document PDF.

```csharp
// create TextExtractor object to extract PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions object to set instructions
    textExtractorOptions = new TextExtractorOptions();
    
    // add input file path to data sources
    textExtractorOptions.AddInput(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Voir aussi

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)