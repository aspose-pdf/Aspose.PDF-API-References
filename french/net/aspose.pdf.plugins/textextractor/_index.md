---
title: Class TextExtractor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.TextExtractor. Représente le plugin TextExtractor
type: docs
weight: 9380
url: /fr/net/aspose.pdf.plugins/textextractor/
---
## Classe TextExtractor

Représente le plugin TextExtractor.

```csharp
public class TextExtractor : PdfExtractor
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextExtractor](textextractor/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implémentation de IDisposable. En fait, ce n'est pas nécessaire pour PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Démarre le traitement de PdfExtractor avec les paramètres spécifiés. |

## Remarques

L'objet `TextExtractor` est utilisé pour extraire du texte dans des documents PDF.

## Exemples

L'exemple démontre comment extraire le contenu textuel d'un document PDF.

```csharp
// create TextExtractor object to extract text in PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions
    textExtractorOptions = new TextExtractorOptions();
    
    // add input file path to data sources
    textExtractorOptions.AddDataSource(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Voir aussi

* classe [PdfExtractor](../pdfextractor/)
* espace de noms [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)