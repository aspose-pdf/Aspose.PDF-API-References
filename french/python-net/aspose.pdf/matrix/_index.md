---
title: "Matrix"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "La classe représente une matrice de transformation."
type: docs
weight: 900
url: /fr/python-net/aspose.pdf/matrix/
---

## Matrix class

La classe représente une matrice de transformation.

Le type Matrix expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| Matrix() | Constructeur<br/>            crée une matrice standard 1 à 1 :<br/>            [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| Matrix(matrix_array) | Initialise une nouvelle instance de la classe Matrix |
| Matrix(matrix_array) | Initialise une nouvelle instance de la classe Matrix |
| Matrix(matrix) | Initialise une nouvelle instance de la classe Matrix |
| Matrix(a, b, c, d, e, f) | Initialise une nouvelle instance de la classe Matrix |
## Propriétés
| Nom | Description |
| :- | :- |
| data | Obtient les données de la Matrix sous forme de tableau. |
| a | Un membre de la matrice de transformation. |
| b | Un membre B de la matrice de transformation. |
| c | Un membre C de la matrice de transformation. |
| d | Un membre D de la matrice de transformation. |
| e | Un membre E de la matrice de transformation. |
| f | Un membre F de la matrice de transformation. |
| éléments | Éléments de la matrice. |
## Méthodes
| Nom | Description |
| :- | :- |
| rotation(alpha) | Crée une matrice pour l'angle de rotation donné. |
| rotation(rotation) | Crée une matrice pour l'angle de rotation donné. |
| transform(p) | Transforme le point en utilisant cette matrice. |
| transform(rect) | Transforme le rectangle.<br/>            Si l'angle n'est pas un multiple de 90 degrés alors le rectangle englobant est renvoyé. |
| skew(alpha, beta) | Crée une matrice pour l'angle de rotation donné. |
| get_angle(rotation) | Traduit la rotation en angle (degrés) |
| multiply(other) | Multiplie la matrice par une autre matrice. |
| add(other) | Ajoute la matrice à une autre matrice. |
| reverse() | Calcule la matrice inverse. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

