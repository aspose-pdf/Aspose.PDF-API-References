---
title: Matrix
second_title: Référence de l'API Aspose.PDF pour .NET
description: La classe représente la matrice de transformation.
type: docs
weight: 4740
url: /fr/net/aspose.pdf/matrix/
---
## Matrix class

La classe représente la matrice de transformation.

```csharp
public sealed class Matrix
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Matrix](matrix#constructor)() | Constructor crée une matrice standard 1 à 1 : [ ABCDEF ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](matrix#constructor_3)(double[]) | Le constructeur accepte une matrice avec la représentation matricielle suivante : [ ABCDEF ] |
| [Matrix](matrix#constructor_4)(float[]) | Le constructeur accepte une matrice avec la représentation matricielle suivante : [ ABCDEF ] |
| [Matrix](matrix#constructor_1)(Matrix) | Constructor accepte une matrice pour créer une copie |
| [Matrix](matrix#constructor_2)(double, double, double, double, double, double) | Initialise la matrice de transformation avec les coefficients spécifiés. |

## Propriétés

| Nom | La description |
| --- | --- |
| [A](../../aspose.pdf/matrix/a) { get; set; } | Un membre de la matrice de transformation. |
| [B](../../aspose.pdf/matrix/b) { get; set; } | Membre B de la matrice de transformation. |
| [C](../../aspose.pdf/matrix/c) { get; set; } | Membre C de la matrice de transformation. |
| [D](../../aspose.pdf/matrix/d) { get; set; } | Membre D de la matrice de transformation. |
| [Data](../../aspose.pdf/matrix/data) { get; } | Obtient les données de Matrix sous forme de tableau. |
| [E](../../aspose.pdf/matrix/e) { get; set; } | E membre de la matrice de transformation. |
| [Elements](../../aspose.pdf/matrix/elements) { get; } | Éléments de la matrice. |
| [F](../../aspose.pdf/matrix/f) { get; set; } | Membre F de la matrice de transformation. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation#rotation_1)(double) | Crée une matrice pour un angle de rotation donné. |
| static [Rotation](../../aspose.pdf/matrix/rotation#rotation)(Rotation) | Crée une matrice pour une rotation donnée. |
| static [Skew](../../aspose.pdf/matrix/skew)(double, double) | Crée une matrice pour un angle de rotation donné. |
| [Add](../../aspose.pdf/matrix/add)(Matrix) | Ajoute une matrice à une autre matrice. |
| override [Equals](../../aspose.pdf/matrix/equals)(object) | Compare la matrice avec un autre objet. |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode)() | Code de hachage pour l'objet. |
| [Multiply](../../aspose.pdf/matrix/multiply)(Matrix) | Multiplie la matrice par une autre matrice. |
| [Reverse](../../aspose.pdf/matrix/reverse)() | Calcule la matrice inverse. |
| override [ToString](../../aspose.pdf/matrix/tostring)() | Renvoie la représentation textuelle de la matrice. |
| [Transform](../../aspose.pdf/matrix/transform#transform)(Point) | Transforme le point en utilisant cette matrice. |
| [Transform](../../aspose.pdf/matrix/transform#transform_1)(Rectangle) | Transforme le rectangle. Si l'angle n'est pas de 90 * N degrés, alors le rectangle englobant est renvoyé. |
| static [GetAngle](../../aspose.pdf/matrix/getangle)(Rotation) | Rotation transaltes en angle (degrés) |

### Voir également

* espace de noms [Aspose.Pdf](../../aspose.pdf)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->