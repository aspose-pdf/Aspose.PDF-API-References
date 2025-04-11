---
title: Class SubPath
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Vector.SubPath. Représente un objet graphique vectoriel sur la page. Fondamentalement, les objets graphiques vectoriels sont représentés par deux groupes de SubPaths. L'un d'eux est représenté par un ensemble de lignes et de courbes. Les autres sont présentés sous forme de rectangles et peuvent parfois être confondus. En général, il s'agit d'une zone rectangulaire qui a une couleur, mais très souvent, ce rectangle est placé au début de la page et définit tout l'espace de la page en blanc. Ainsi, vous obtenez le SubPath, mais visuellement, vous ne voyez que le texte sur la page.
type: docs
weight: 11220
url: /fr/net/aspose.pdf.vector/subpath/
---
## Classe SubPath

Représente un objet graphique vectoriel sur la page. Fondamentalement, les objets graphiques vectoriels sont représentés par deux groupes de SubPaths. L'un d'eux est représenté par un ensemble de lignes et de courbes. Les autres sont présentés sous forme de rectangles et peuvent parfois être confondus. En général, il s'agit d'une zone rectangulaire qui a une couleur, mais très souvent, ce rectangle est placé au début de la page et définit tout l'espace de la page en blanc. Ainsi, vous obtenez le SubPath, mais visuellement, vous ne voyez que le texte sur la page.

```csharp
public sealed class SubPath : GraphicElement
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Obtient la matrice de l'élément graphique. La matrice est définie lors de la création de l'élément. Elle change lorsque SetPosition() est appelé. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Obtient une collection d'opérateurs représentant l'élément. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Obtient le [`XFormPlacement`](../xformplacement/) actuel dans lequel se trouve l'élément. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Obtient ou définit la position dans l'espace de coordonnées actuel. Si [`Parent`](../graphicelement/parent/) n'est pas !:null alors l'élément a un espace de coordonnées xForm. |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Obtient la page à partir de laquelle l'élément graphique est extrait. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Ajoute l'élément actuel sur la page. S'il y a de nombreux éléments à ajouter, il est préférable d'utiliser [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Libère toutes les ressources utilisées par la classe [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Supprime l'élément actuel de la page. S'il y a de nombreux éléments à supprimer, il est préférable d'utiliser [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Convertit l'élément en une seule image SVG. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Convertit l'élément en un fichier image SVG unique. |

### Voir aussi

* classe [GraphicElement](../graphicelement/)
* espace de noms [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)