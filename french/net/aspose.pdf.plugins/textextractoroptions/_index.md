---
title: "Classe TextExtractorOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Plugins.TextExtractorOptions. Représente les options d'extraction de texte pour le plugin TextExtractor."
type: docs
weight: 9540
url: /fr/net/aspose.pdf.plugins/textextractoroptions/
---
## TextExtractorOptions class

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

## Autres membres

| Nom | Description |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | Définit différents modes qui peuvent être utilisés lors de la conversion d'un document PDF en texte. Voir la classe `TextExtractorOptions`. |

## Remarques

L'objet `TextExtractorOptions` est utilisé pour définir [`TextFormattingMode`](../textextractoroptions.textformattingmode/) et d'autres options pour l'opération d'extraction de texte. De plus, il hérite des fonctions permettant d'ajouter des données (fichiers, flux) représentant les documents PDF d'entrée.

## Exemples

L'exemple montre comment extraire le contenu texte d'un document PDF.

```csharp
// créez un objet TextExtractor pour extraire le contenu PDF.
using (TextExtractor extractor = new TextExtractor())
{
    // créez un objet TextExtractorOptions pour définir TextFormattingMode (Pure, ou Raw - par défaut)
    extractorOptions = new TextExtractorOptions(TextExtractorOptions.TextFormattingMode.Pure);
    
    // ajoutez le chemin du fichier d'entrée aux sources de données
    extractorOptions.AddInput(new FileDataSource(inputPath));
    
    // exécuter le processus d'extraction
    ResultContainer resultContainer = extractor.Process(extractorOptions);
    
    // obtenez le texte extrait depuis l'objet ResultContainer
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Voir aussi

* class [PdfExtractorOptions](../pdfextractoroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


