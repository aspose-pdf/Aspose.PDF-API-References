---
title: "Classe TextAbsorber"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Text.TextAbsorber. Représente un objet absorbeur de texte. Effectue l’extraction de texte et fournit l’accès au résultat via l’objet Text."
type: docs
weight: 10980
url: /fr/net/aspose.pdf.text/textabsorber/
---
## TextAbsorber class

Représente un objet absorbeur de texte. Effectue l’extraction de texte et fournit l’accès au résultat via l’objet [`Text`](./text/).

```csharp
public class TextAbsorber
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextAbsorber](textabsorber/#constructor)() | Initialise une nouvelle instance de `TextAbsorber`. |
| [TextAbsorber](textabsorber/#constructor_1)(TextExtractionOptions) | Initialise une nouvelle instance de `TextAbsorber` avec des options d’extraction. |
| [TextAbsorber](textabsorber/#constructor_3)(TextSearchOptions) | Initialise une nouvelle instance de `TextAbsorber` avec des options de recherche de texte. |
| [TextAbsorber](textabsorber/#constructor_2)(TextExtractionOptions, TextSearchOptions) | Initialise une nouvelle instance de `TextAbsorber` avec des options d’extraction et de recherche de texte. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | Liste d'objets [`TextExtractionError`](../textextractionerror/). Elle contient des informations sur les erreurs trouvées lors de l'extraction de texte. La recherche d'erreurs ne sera effectuée que si TextSearchOptions.LogTextExtractionErrors = true ; et cela peut diminuer les performances. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | Obtient ou définit les options d'extraction de texte. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | La valeur indique si des erreurs ont été trouvées lors de l'extraction du texte. La recherche d'erreurs ne sera effectuée que si TextSearchOptions.LogTextExtractionErrors = true ; et cela peut diminuer les performances. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | Obtient le texte extrait que le `TextAbsorber` récupère sur le document PDF ou la page. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | Obtient ou définit les options de recherche de texte. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | Extrait le texte du document spécifié |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | Extrait le texte de la page spécifiée |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | Extrait le texte sur le XForm spécifié. |

## Remarques

L’objet `TextAbsorber` est utilisé pour extraire du texte d’un document Pdf ou de la page du document.

## Exemples

L’exemple montre comment extraire du texte sur la première page du document PDF.

```csharp
// ouvrir le document
Document doc = new Document(inFile);

// créer un objet TextAbsorber pour extraire du texte
TextAbsorber absorber = new TextAbsorber();

// accepter l'absorbeur pour la première page
doc.Pages[1].Accept(absorber);

// obtenir le texte extrait
string extractedText = absorber.Text;

```

### Voir aussi

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


