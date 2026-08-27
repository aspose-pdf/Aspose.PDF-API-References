---
title: "ParagraphAbsorber"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente un objet absorbeur des objets de structure de page tels que les sections et les paragraphes.<br/>            Effectue la recherche de sections et de paragraphes de texte et fournit l'accès aux rectangles et aux polygones qui les décrivent dans l'espace de coordonnées du texte. <br/>            Effectue également la recherche de segments de texte et fournit l'accès aux résultats de recherche via les collections TextFragments regroupées par éléments de structure."
type: docs
weight: 240
url: /fr/python-net/aspose.pdf.text/paragraphabsorber/
---

## ParagraphAbsorber class

Représente un objet absorbeur des objets de structure de page tels que les sections et les paragraphes.<br/>            Effectue la recherche de sections et de paragraphes de texte et fournit l'accès aux rectangles et aux polygones qui les décrivent dans l'espace de coordonnées du texte. <br/>            Effectue également la recherche de segments de texte et fournit l'accès aux résultats de recherche via les collections TextFragments regroupées par éléments de structure.

Le type ParagraphAbsorber expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| ParagraphAbsorber() | Initialise une nouvelle instance de [ParagraphAbsorber](/pdf/python-net/aspose.pdf.text/paragraphabsorber/) qui effectue la recherche de sections/paragraphe du document ou de la page. |
| ParagraphAbsorber(sections_search_depth) | Initialise une nouvelle instance de la classe ParagraphAbsorber |
## Propriétés
| Nom | Description |
| :- | :- |
| page_markups | Obtient la collection de [PageMarkup](/pdf/python-net/aspose.pdf.text/pagemarkup/) qui ont été absorbées. |
| sections_search_depth | Obtient ou définit la valeur qui indique combien de fois les recherches séquentielles pour des éléments de structure plus fins seront effectuées.<br/>            La profondeur de recherche par défaut est de 3.<br/>            Cela signifie trois recherches pour les sections divisées horizontalement (en-têtes, paragraphes, etc.) et trois recherches pour celles divisées verticalement (colonnes). |
| is_multicolumn_paragraphs_allowed | Obtient ou définit la valeur qui indique si les lignes de texte de début d'une section suivante peuvent être traitées comme la continuation du dernier paragraphe d'une section précédente. |
## Méthodes
| Nom | Description |
| :- | :- |
| visit(doc) | Effectue la recherche de sections et de paragraphes dans le [Document](/pdf/python-net/aspose.pdf/document/) spécifié. |
| visit(page) | Effectue une recherche sur la [Page](/pdf/python-net/aspose.pdf/page/). |

### Voir aussi

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

