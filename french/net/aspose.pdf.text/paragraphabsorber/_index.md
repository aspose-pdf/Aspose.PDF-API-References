---
title: Class ParagraphAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.ParagraphAbsorber. Représente un objet absorbeur d'objets de structure de page tels que des sections et des paragraphes. Effectue une recherche de sections et de paragraphes de texte et fournit un accès aux rectangles et polygones qui les décrivent dans l'espace de coordonnées de texte. Effectue également une recherche de segments de texte et fournit un accès aux résultats de recherche via des collections de TextFragments regroupées par éléments de structure.
type: docs
weight: 10670
url: /fr/net/aspose.pdf.text/paragraphabsorber/
---
## Classe ParagraphAbsorber

Représente un objet absorbeur d'objets de structure de page tels que des sections et des paragraphes. Effectue une recherche de sections et de paragraphes de texte et fournit un accès aux rectangles et polygones qui les décrivent dans l'espace de coordonnées de texte. Effectue également une recherche de segments de texte et fournit un accès aux résultats de recherche via des collections de !:TextFragments regroupées par éléments de structure.

```csharp
public class ParagraphAbsorber
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | Initialise une nouvelle instance de `ParagraphAbsorber` qui effectue une recherche de sections/paragraphes du document ou de la page. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | Initialise une nouvelle instance de `ParagraphAbsorber` qui effectue une recherche de sections/paragraphes du document ou de la page. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | Initialise une nouvelle instance de `ParagraphAbsorber` qui effectue une recherche de sections/paragraphes du document ou de la page avec les paramètres spécifiés. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | Initialise une nouvelle instance de `ParagraphAbsorber` qui effectue une recherche de sections/paragraphes du document ou de la page avec les paramètres spécifiés. |

## Propriétés

| Nom | Description |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | Obtient ou définit la valeur qui indique si les lignes de texte de début d'une section suivante peuvent être considérées comme une continuation du dernier paragraphe d'une section précédente. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | Obtient la collection de [`PageMarkup`](../pagemarkup/) qui ont été absorbés. |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | Obtient ou définit les options de ParagraphAbsorber. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | Obtient ou définit la valeur qui indique combien de fois des recherches séquentielles pour des éléments de structure plus fins seront effectuées. La profondeur de recherche par défaut est de 3. Cela signifie trois recherches pour des sections divisées horizontalement (en-têtes, paragraphes, etc.) et trois recherches pour celles divisées verticalement (colonnes). |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | Obtient ou définit les options de remplacement de texte. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | Effectue une recherche de sections et de paragraphes sur le [`Document`](../../aspose.pdf/document/) spécifié. |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | Effectue une recherche sur la [`Page`](../../aspose.pdf/page/) spécifiée. |

## Remarques

Lorsque la recherche est terminée, la collection [`PageMarkups`](./pagemarkups/) contiendra des objets [`PageMarkup`](../pagemarkup/) qui représentent la structure de la page par des collections de [`MarkupSection`](../markupsection/) et [`MarkupParagraph`](../markupparagraph/). L'objet [`TextFragment`](../textfragment/) fournit un accès au texte d'occurrence de la recherche, aux propriétés du texte, et permet d'éditer le texte et de changer l'état du texte (police, taille de police, couleur, etc.).

## Exemples

L'exemple démontre comment trouver le premier segment de texte de chaque paragraphe sur la première page du document PDF et le mettre en surbrillance.

```csharp
// Open document
Document doc = new Document("input.pdf");

// Create ParagraphAbsorber object
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Get markup object of first page
PageMarkup markup = absorber.PageMarkups[0];

// Loop through structure elements of the page text to find first text fragment of each paragraph
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // Update text properties
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// Save document
doc.Save(GetOutputPath("output.pdf"));
```

### Voir aussi

* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)