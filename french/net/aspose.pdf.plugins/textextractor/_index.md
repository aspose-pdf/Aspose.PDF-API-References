---
title: "Classe TextExtractor"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Plugins.TextExtractor. Représente le plugin TextExtractor"
type: docs
weight: 9530
url: /fr/net/aspose.pdf.plugins/textextractor/
---
## TextExtractor class

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
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Démarre le traitement PdfExtractor avec les paramètres spécifiés. |

## Remarques

L'objet `TextExtractor` est utilisé pour extraire du texte dans les documents PDF.

## Exemples

L'exemple montre comment extraire le contenu texte d'un document PDF.

```csharp
// créer un objet TextExtractor pour extraire du texte dans le contenu PDF
using (TextExtractor extractor = new TextExtractor())
{
    // créer TextExtractorOptions
    textExtractorOptions = new TextExtractorOptions();
    
    // ajoutez le chemin du fichier d'entrée aux sources de données
    textExtractorOptions.AddDataSource(new FileDataSource(inputPath));
    
    // exécuter le processus d'extraction
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // obtenez le texte extrait depuis l'objet ResultContainer
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Voir aussi

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


