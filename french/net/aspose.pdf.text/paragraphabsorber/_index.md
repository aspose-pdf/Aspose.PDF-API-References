---
title: ParagraphAbsorber
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente un objet absorbeur dobjets de structure de page tels que des sections et des paragraphes. Effectue une recherche de sections et de paragraphes de texte et permet daccéder à des rectangles et des polydons qui le décrivent dans lespace de coordonnées du texte. Effectue également une recherche de segments de texte et permet daccéder aux résultats de la recherche viaTextFragments collections regroupées par éléments de structure.
type: docs
weight: 6850
url: /fr/net/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber class

Représente un objet absorbeur d'objets de structure de page tels que des sections et des paragraphes. Effectue une recherche de sections et de paragraphes de texte et permet d'accéder à des rectangles et des polydons qui le décrivent dans l'espace de coordonnées du texte. Effectue également une recherche de segments de texte et permet d'accéder aux résultats de la recherche via!:TextFragments collections regroupées par éléments de structure.

```csharp
public class ParagraphAbsorber
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber#constructor)() | Initialise une nouvelle instance du[`ParagraphAbsorber`](../paragraphabsorber) qui effectue la recherche de sections/paragraphes du document ou de la page. |
| [ParagraphAbsorber](paragraphabsorber#constructor_1)(int) | Initialise une nouvelle instance du[`ParagraphAbsorber`](../paragraphabsorber) qui effectue la recherche de sections/paragraphes du document ou de la page. |

## Propriétés

| Nom | La description |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed) { get; set; } | Obtient ou définit une valeur qui indique si les premières lignes de texte d'une section suivante peuvent être traitées comme la continuation du dernier paragraphe d'une section précédente. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups) { get; } | Obtient la collection de[`PageMarkup`](../pagemarkup) qui ont été absorbés. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth) { get; set; } | Obtient ou définit la valeur qui indique combien de fois des recherches séquentielles d'éléments de structure plus fins seront effectuées. La profondeur de recherche par défaut est de 3. Cela signifie trois recherches pour les sections divisées horizontalement (en-têtes, paragraphes, etc.) et trois recherches pour les sections divisées verticalement ceux (colonnes). |

## Méthodes

| Nom | La description |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit#visit)(Document) | Effectue une recherche de sections et de paragraphes sur le[`Document`](../../aspose.pdf/document) . |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit#visit_1)(Page) | Effectue une recherche sur le[`Page`](../../aspose.pdf/page) . |

### Remarques

Lorsque la recherche est terminée, le[`PageMarkups`](./pagemarkups) la collection contiendra[`PageMarkup`](../pagemarkup) objets qui représentent la structure de la page par des collections de[`MarkupSection`](../markupsection) et[`MarkupParagraph`](../markupparagraph) . Le[`TextFragment`](../textfragment) L'objet donne accès au texte de l'occurrence de recherche, aux propriétés du texte et permet de modifier le texte et de changer l'état du texte (police, taille de police, couleur, etc.).

### Exemples

L'exemple montre comment trouver le premier segment de texte de chaque paragraphe sur la première page du document PDF et le mettre en surbrillance.

```csharp
// Ouvrir le document
Document doc = new Document("input.pdf");

// Créer un objet ParagraphAbsorber
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Accepte l'absorbeur pour la première page
absorber.Visit(doc.Pages[1]);

// Récupère l'objet de balisage de la première page
PageMarkup markup = absorber.PageMarkups[0];

// Boucle à travers les éléments de structure du texte de la page pour trouver le premier fragment de texte de chaque paragraphe
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

### Voir également

* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->