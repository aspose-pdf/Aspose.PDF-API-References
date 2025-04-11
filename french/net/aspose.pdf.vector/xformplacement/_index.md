---
title: Class XFormPlacement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Vector.XFormPlacement. Représente le placement de XForm. Si le XForm est affiché sur la page plus d'une fois, tous les XformPlacements associés à ce XForm auront des éléments graphiques communs mais des états graphiques différents.
type: docs
weight: 11260
url: /fr/net/aspose.pdf.vector/xformplacement/
---
## Classe XFormPlacement

Représente le placement de XForm. Si le XForm est affiché sur la page plus d'une fois, tous les XformPlacements associés à ce XForm auront des éléments graphiques communs, mais des états graphiques différents.

```csharp
public sealed class XFormPlacement : GraphicElement
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | Obtient les éléments graphiques à l'intérieur de ce XForm. |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Obtient la matrice de l'élément graphique. La matrice est définie lors de la création de l'élément. Elle change lorsque SetPosition() est appelé. |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | Obtient le nom du XForm. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Obtient une collection d'opérateurs représentant l'élément. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Obtient le `XFormPlacement` actuel dans lequel se trouve l'élément. |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Obtient la page à partir de laquelle l'élément graphique est extrait. |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | Obtient le XForm associé à ce XFormPlacement. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | Ajoute l'élément actuel sur la page. S'il y a de nombreux éléments à ajouter, il est préférable d'utiliser [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Libère toutes les ressources utilisées par la classe [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Supprime l'élément actuel de la page. S'il y a de nombreux éléments à supprimer, il est préférable d'utiliser [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Convertit l'élément en une seule image SVG. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Convertit l'élément en un fichier image SVG unique. |

### Voir aussi

* classe [GraphicElement](../graphicelement/)
* espace de noms [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)