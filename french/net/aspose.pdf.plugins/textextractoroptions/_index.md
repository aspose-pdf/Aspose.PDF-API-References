---
title: Class TextExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.TextExtractorOptions. Représente les options d'extraction de texte pour le plugin TextExtractor
type: docs
weight: 9390
url: /fr/net/aspose.pdf.plugins/textextractoroptions/
---
## Classe TextExtractorOptions

Représente les options d'extraction de texte pour le plugin TextExtractor.

```csharp
public sealed class TextExtractorOptions : PdfExtractorOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextExtractorOptions](textextractoroptions/#constructor)() | Initialise une nouvelle instance de l'objet `TextExtractorOptions` avec le mode de formatage de texte 'Raw' (par défaut). |
| [TextExtractorOptions](textextractoroptions/#constructor_1)(TextFormattingMode) | Initialise une nouvelle instance de l'objet `TextExtractorOptions` pour le mode de formatage de texte spécifié. |

## Propriétés

| Nom | Description |
| --- | --- |
| [FormattingMode](../../aspose.pdf.plugins/textextractoroptions/formattingmode/) { get; } | Obtient le mode de formatage. |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | Renvoie la collection de données du plugin PdfExtractor. |
| override [OperationName](../../aspose.pdf.plugins/textextractoroptions/operationname/) { get; } | Renvoie le nom de l'opération. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | Ajoute une nouvelle source de données à la collection de données du plugin PdfExtractor. |

## Autres Membres

| Nom | Description |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | Définit différents modes qui peuvent être utilisés lors de la conversion d'un document PDF en texte. Voir la classe `TextExtractorOptions`. |

## Remarques

L'objet `TextExtractorOptions` est utilisé pour définir [`TextFormattingMode`](../textextractoroptions.textformattingmode/) et d'autres options pour l'opération d'extraction de texte. De plus, il hérite des fonctions pour ajouter des données (fichiers, flux) représentant des documents PDF d'entrée.

## Exemples

L'exemple démontre comment extraire le contenu textuel d'un document PDF.

```csharp
// create TextExtractor object to extract PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions object to set TextFormattingMode (Pure,  or Raw - default)
    extractorOptions = new TextExtractorOptions(TextExtractorOptions.TextFormattingMode.Pure);
    
    // add input file path to data sources
    extractorOptions.AddInput(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(extractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Voir aussi

* classe [PdfExtractorOptions](../pdfextractoroptions/)
* espace de noms [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)