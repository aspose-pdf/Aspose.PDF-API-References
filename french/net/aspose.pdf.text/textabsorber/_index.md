---
title: Class TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextAbsorber. Représente un objet absorbeur de texte. Effectue l'extraction de texte et fournit un accès au résultat via l'objet [`Text`](./text/).
type: docs
weight: 10800
url: /fr/net/aspose.pdf.text/textabsorber/
---
## Classe TextAbsorber

Représente un objet absorbeur de texte. Effectue l'extraction de texte et fournit un accès au résultat via l'objet [`Text`](./text/).

```csharp
public class TextAbsorber
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextAbsorber](textabsorber/#constructor)() | Initialise une nouvelle instance de `TextAbsorber`. |
| [TextAbsorber](textabsorber/#constructor_1)(TextExtractionOptions) | Initialise une nouvelle instance de `TextAbsorber` avec des options d'extraction. |
| [TextAbsorber](textabsorber/#constructor_3)(TextSearchOptions) | Initialise une nouvelle instance de `TextAbsorber` avec des options de recherche de texte. |
| [TextAbsorber](textabsorber/#constructor_2)(TextExtractionOptions, TextSearchOptions) | Initialise une nouvelle instance de `TextAbsorber` avec des options d'extraction et de recherche de texte. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | Liste des objets [`TextExtractionError`](../textextractionerror/). Elle contient des informations sur les erreurs trouvées lors de l'extraction de texte. La recherche d'erreurs ne sera effectuée que si TextSearchOptions.LogTextExtractionErrors = true; et cela peut diminuer les performances. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | Obtient ou définit les options d'extraction de texte. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | La valeur indique si des erreurs ont été trouvées lors de l'extraction de texte. La recherche d'erreurs ne sera effectuée que si TextSearchOptions.LogTextExtractionErrors = true; et cela peut diminuer les performances. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | Obtient le texte extrait que le `TextAbsorber` extrait du document ou de la page PDF. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | Obtient ou définit les options de recherche de texte. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | Extrait le texte du document spécifié |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | Extrait le texte de la page spécifiée |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | Extrait le texte du XForm spécifié. |

## Remarques

L'objet `TextAbsorber` est utilisé pour extraire du texte d'un document Pdf ou de la page du document.

## Exemples

L'exemple démontre comment extraire du texte sur la première page du document PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### Voir aussi

* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)