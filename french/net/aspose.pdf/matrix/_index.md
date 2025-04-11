---
title: Class Matrix
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Matrix. La classe représente une matrice de transformation
type: docs
weight: 6920
url: /fr/net/aspose.pdf/matrix/
---
## Classe Matrix

La classe représente une matrice de transformation.

```csharp
public sealed class Matrix
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Matrix](matrix/#constructor)() | Le constructeur crée une matrice standard 1 à 1 : [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](matrix/#constructor_3)(double[]) | Le constructeur accepte une matrice avec la représentation de tableau suivante : [ A B C D E F ] |
| [Matrix](matrix/#constructor_4)(float[]) | Le constructeur accepte une matrice avec la représentation de tableau suivante : [ A B C D E F ] |
| [Matrix](matrix/#constructor_1)(Matrix) | Le constructeur accepte une matrice pour créer une copie |
| [Matrix](matrix/#constructor_2)(double, double, double, double, double, double) | Initialise la matrice de transformation avec les coefficients spécifiés. |

## Propriétés

| Nom | Description |
| --- | --- |
| [A](../../aspose.pdf/matrix/a/) { get; set; } | Un membre de la matrice de transformation. |
| [B](../../aspose.pdf/matrix/b/) { get; set; } | Membre B de la matrice de transformation. |
| [C](../../aspose.pdf/matrix/c/) { get; set; } | Membre C de la matrice de transformation. |
| [D](../../aspose.pdf/matrix/d/) { get; set; } | Membre D de la matrice de transformation. |
| [Data](../../aspose.pdf/matrix/data/) { get; } | Obtient les données de la matrice sous forme de tableau. |
| [E](../../aspose.pdf/matrix/e/) { get; set; } | Membre E de la matrice de transformation. |
| [Elements](../../aspose.pdf/matrix/elements/) { get; } | Éléments de la matrice. |
| [F](../../aspose.pdf/matrix/f/) { get; set; } | Membre F de la matrice de transformation. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation_1)(double) | Crée une matrice pour un angle de rotation donné. |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation)(Rotation) | Crée une matrice pour une rotation donnée. |
| static [Scale](../../aspose.pdf/matrix/scale/)(double, double, Matrix) | Applique un redimensionnement à la matrice donnée. |
| static [Skew](../../aspose.pdf/matrix/skew/)(double, double) | Crée une matrice pour un angle de rotation donné. |
| static [Translate](../../aspose.pdf/matrix/translate/)(double, double, Matrix) | Traduit une matrice par le montant spécifié dans la direction x et y. |
| [Add](../../aspose.pdf/matrix/add/)(Matrix) | Ajoute une matrice à une autre matrice. |
| override [Equals](../../aspose.pdf/matrix/equals/)(object) | Compare la matrice à un autre objet. |
| [GetFlipMatrix](../../aspose.pdf/matrix/getflipmatrix/)() | Obtient la matrice de retournement. |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode/)() | Code de hachage pour l'objet. |
| [Multiply](../../aspose.pdf/matrix/multiply/)(Matrix) | Multiplie la matrice par une autre matrice. |
| [Reverse](../../aspose.pdf/matrix/reverse/)() | Calcule la matrice inverse. |
| [Scale](../../aspose.pdf/matrix/scale/)(double, double, out double, out double) | Redimensionne x et y avec la matrice en utilisant la formule suivante : x1 = A*x + C*y; y1 = B*x + D*y; |
| override [ToString](../../aspose.pdf/matrix/tostring/)() | Renvoie la représentation textuelle de la matrice. |
| [Transform](../../aspose.pdf/matrix/transform/#transform)(Point) | Transforme le point en utilisant cette matrice. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_1)(Rectangle) | Transforme le rectangle. Si l'angle n'est pas un multiple de 90 degrés, alors le rectangle englobant est renvoyé. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_2)(double, double, out double, out double) | Transforme les coordonnées en utilisant cette matrice. |
| [UnScale](../../aspose.pdf/matrix/unscale/)(double, double, out double, out double) | Redimensionne x1 et y1 et renvoie x et y avant la transformation de la matrice en utilisant la formule suivante : x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [UnTransform](../../aspose.pdf/matrix/untransform/)(double, double, out double, out double) | Transforme x1 et y1 et renvoie x et y avant la transformation de la matrice en utilisant la formule suivante : x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |
| static [GetAngle](../../aspose.pdf/matrix/getangle/)(Rotation) | Traduit la rotation en angle (degrés) |

### Voir aussi

* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)