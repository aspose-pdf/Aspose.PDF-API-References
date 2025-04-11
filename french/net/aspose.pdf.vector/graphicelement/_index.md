---
title: Class GraphicElement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Vector.GraphicElement. Représente la classe de base pour les objets graphiques sur la page
type: docs
weight: 11180
url: /fr/net/aspose.pdf.vector/graphicelement/
---
## Classe GraphicElement

Représente la classe de base pour les objets graphiques sur la page.

```csharp
public abstract class GraphicElement : IDisposable
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Obtient la matrice de l'élément graphique. La matrice est définie lors de la création de l'élément. Elle change lorsque SetPosition() est appelé. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Obtient une collection d'opérateurs représentant l'élément. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Obtient le [`XFormPlacement`](../xformplacement/) actuel dans lequel se trouve l'élément. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Obtient ou définit la position dans l'espace de coordonnées actuel. Si [`Parent`](./parent/) n'est pas !:null alors l'élément a un espace de coordonnées xForm. |
| abstract [Rectangle](../../aspose.pdf.vector/graphicelement/rectangle/) { get; } | Obtient le rectangle englobant du `GraphicElement`. |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Obtient la page à partir de laquelle l'élément graphique est extrait. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Ajoute l'élément actuel sur la page. S'il y a de nombreux éléments à ajouter, il est préférable d'utiliser [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Libère toutes les ressources utilisées par la classe `GraphicElement`. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Supprime l'élément actuel de la page. S'il y a de nombreux éléments à supprimer, il est préférable d'utiliser [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg)() | Convertit l'élément en une seule image SVG. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg_1)(string) | Convertit l'élément en un fichier image SVG unique. |

### Voir aussi

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)