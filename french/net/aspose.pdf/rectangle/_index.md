---
title: Class Rectangle
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Rectangle. La classe représente un rectangle
type: docs
weight: 9750
url: /fr/net/aspose.pdf/rectangle/
---
## Classe Rectangle

La classe représente un rectangle.

```csharp
public sealed class Rectangle : ICloneable
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Rectangle](rectangle/)(double, double, double, double, bool) | Constructeur de Rectangle. |

## Propriétés

| Nom | Description |
| --- | --- |
| static [Empty](../../aspose.pdf/rectangle/empty/) { get; } | Rectangle vide |
| static [Trivial](../../aspose.pdf/rectangle/trivial/) { get; } | Initialise un rectangle trivial c'est-à-dire un rectangle avec une position et une taille nulles. |
| [Height](../../aspose.pdf/rectangle/height/) { get; } | Hauteur du rectangle. |
| [IsEmpty](../../aspose.pdf/rectangle/isempty/) { get; } | Vérifie si le rectangle est vide. |
| [IsPoint](../../aspose.pdf/rectangle/ispoint/) { get; } | Vérifie si le rectangle est un point c'est-à-dire que LLX est égal à URX et LLY est égal à URY. |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial/) { get; } | Vérifie si le rectangle est trivial c'est-à-dire a une taille et une position nulles. |
| [LLX](../../aspose.pdf/rectangle/llx/) { get; set; } | Coordonnée X du coin inférieur gauche. |
| [LLY](../../aspose.pdf/rectangle/lly/) { get; set; } | Coordonnée Y du coin inférieur gauche. |
| [URX](../../aspose.pdf/rectangle/urx/) { get; set; } | Coordonnée X du coin supérieur droit. |
| [URY](../../aspose.pdf/rectangle/ury/) { get; set; } | Coordonnée Y du coin supérieur droit. |
| [Width](../../aspose.pdf/rectangle/width/) { get; } | Largeur du rectangle. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect)(Rectangle) | Initialise un nouveau rectangle à partir de l'instance donnée de System.Drawing.Rectangle. |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect_1)(RectangleF) | Initialise un nouveau rectangle à partir de l'instance donnée de System.Drawing.Rectangle. |
| static [Parse](../../aspose.pdf/rectangle/parse/)(string) | Essaie d'analyser la chaîne et d'en extraire les composants du rectangle llx, lly, urx, ury. |
| [Center](../../aspose.pdf/rectangle/center/)() | Renvoie les coordonnées du centre du rectangle. |
| [Clone](../../aspose.pdf/rectangle/clone/)() | Clone l'objet Rectangle. |
| [Contains](../../aspose.pdf/rectangle/contains/)(Point, bool) | Détermine si le point donné est à l'intérieur du rectangle. |
| [ContainsLine](../../aspose.pdf/rectangle/containsline/)(double, double, double, double) | Détermine si le rectangle contient une ligne représentée par deux points. |
| [ContainsPoint](../../aspose.pdf/rectangle/containspoint/)(double, double) | Détermine si le point donné est contenu dans le rectangle. |
| [Equals](../../aspose.pdf/rectangle/equals/#equals)(Rectangle) | Vérifie si les rectangles sont égaux c'est-à-dire ont la même position et les mêmes tailles. |
| [Intersect](../../aspose.pdf/rectangle/intersect/)(Rectangle) | Intersecte deux rectangles. |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect/)(Rectangle) | Détermine si ce rectangle intersecte un autre rectangle. |
| [Join](../../aspose.pdf/rectangle/join/)(Rectangle) | Joint des rectangles. |
| [MoveBy](../../aspose.pdf/rectangle/moveby/)(double, double) | Déplace le rectangle par les deltas spécifiés. |
| [NearEquals](../../aspose.pdf/rectangle/nearequals/)(Rectangle, double) | Vérifie si les rectangles sont presque égaux c'est-à-dire ont presque la même position et les mêmes tailles (jusqu'à delta). |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate_1)(int) | Fait pivoter le rectangle par l'angle spécifié. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate)(Rotation) | Fait pivoter le rectangle par l'angle spécifié. |
| [ToPoints](../../aspose.pdf/rectangle/topoints/)() | Convertit le rectangle en tableau de points ("QuadPoints"). |
| [ToRect](../../aspose.pdf/rectangle/torect/)() | Convertit le rectangle en instance de System.Drawing.Rectangle. Les positions et tailles à virgule flottante sont tronquées. |
| override [ToString](../../aspose.pdf/rectangle/tostring/)() | Obtient la représentation sous forme de chaîne du rectangle. |

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)