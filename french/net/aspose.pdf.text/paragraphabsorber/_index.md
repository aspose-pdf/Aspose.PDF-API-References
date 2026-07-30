---
title: "Classe ParagraphAbsorber"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Text.ParagraphAbsorber classe. Représente un objet absorbeur des objets de structure de page tels que les sections et les paragraphes. Effectue une recherche des sections et des paragraphes de texte et fournit l'accès aux rectangles et aux polygones qui les décrivent dans l'espace de coordonnées du texte. Effectue également une recherche de segments de texte et fournit l'accès aux résultats de recherche via les collections TextFragments regroupées par éléments de structure."
type: docs
weight: 10850
url: /fr/net/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber class

Représente un objet absorbeur d'objets de structure de page tels que les sections et les paragraphes. Effectue une recherche de sections et de paragraphes de texte et fournit l'accès aux rectangles et aux polygones qui les décrivent dans l'espace de coordonnées du texte. Effectue également une recherche de segments de texte et fournit l'accès aux résultats de recherche via les collections !:TextFragments regroupées par éléments de structure.

```csharp
public class ParagraphAbsorber
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | Initialise une nouvelle instance de `ParagraphAbsorber` qui effectue une recherche des sections/paragraphes du document ou de la page. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | Initialise une nouvelle instance de `ParagraphAbsorber` qui effectue une recherche des sections/paragraphes du document ou de la page. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | Initialise une nouvelle instance de `ParagraphAbsorber` qui effectue une recherche des sections/paragraphes du document ou de la page avec les paramètres spécifiés. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | Initialise une nouvelle instance de `ParagraphAbsorber` qui effectue une recherche des sections/paragraphes du document ou de la page avec les paramètres spécifiés. |

## Propriétés

| Nom | Description |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | Obtient ou définit la valeur indiquant si les lignes de texte de départ d'une section suivante peuvent être considérées comme la continuation du dernier paragraphe d'une section précédente. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | Obtient la collection de [`PageMarkup`](../pagemarkup/) qui ont été absorbés. |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | Obtient ou définit les ParagraphAbsorberOptions. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | Obtient ou définit la valeur qui indique combien de fois les recherches séquentielles pour des éléments de structure plus fins seront effectuées. La profondeur de recherche par défaut est de 3. Cela signifie trois recherches pour les sections divisées horizontalement (en-têtes, paragraphes, etc.) et trois recherches pour celles divisées verticalement (colonnes). |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | Obtient ou définit les TextReplaceOptions. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | Effectue une recherche des sections et des paragraphes sur le [`Document`](../../aspose.pdf/document/) spécifié. |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | Effectue une recherche sur la [`Page`](../../aspose.pdf/page/) spécifiée. |

## Remarques

Lorsque la recherche est terminée, la collection [`PageMarkups`](./pagemarkups/) contiendra les objets [`PageMarkup`](../pagemarkup/) qui représentent la structure de la page par des collections de [`MarkupSection`](../markupsection/) et de [`MarkupParagraph`](../markupparagraph/). L'objet [`TextFragment`](../textfragment/) fournit l'accès au texte de l'occurrence recherchée, aux propriétés du texte, et permet de modifier le texte et de changer l'état du texte (police, taille de police, couleur, etc.).

## Exemples

L'exemple montre comment trouver le premier segment de texte de chaque paragraphe sur la première page du document PDF et le mettre en surbrillance.

```csharp
// Ouvrir le document
Document doc = new Document("input.pdf");

// Créer un objet ParagraphAbsorber
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Accepter l'absorbeur pour la première page
absorber.Visit(doc.Pages[1]);

// Obtenir l'objet de balisage de la première page
PageMarkup markup = absorber.PageMarkups[0];

// Parcourir les éléments de structure du texte de la page pour trouver le premier fragment de texte de chaque paragraphe
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // Mettre à jour les propriétés du texte
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// Enregistrer le document
doc.Save(GetOutputPath("output.pdf"));
```

### Voir aussi

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


