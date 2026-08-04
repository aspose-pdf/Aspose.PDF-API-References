---
title: "Rectangle"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "La classe représente un rectangle."
type: docs
weight: 1320
url: /fr/python-net/aspose.pdf/rectangle/
---

## Rectangle class

La classe représente un rectangle.

Le type Rectangle expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| Rectangle(llx, lly, urx, ury, normalize_coordinates) | Initialise une nouvelle instance de la classe Rectangle |
## Propriétés
| Nom | Description |
| :- | :- |
| largeur | Largeur du rectangle. |
| hauteur | Hauteur du rectangle. |
| llx | Coordonnée X du coin inférieur gauche. |
| lly | Coordonnée Y du coin inférieur gauche. |
| urx | Coordonnée X du coin supérieur droit. |
| ury | Coordonnée Y du coin supérieur droit. |
| trivial | Initialise un rectangle trivial, c’est‑à‑dire un rectangle avec une position et une taille nulles. |
| is_trivial | Vérifie si le rectangle est trivial, c’est‑à‑dire s’il a une taille et une position nulles. |
| is_empty | Vérifie si le rectangle est vide. |
| is_point | Vérifie si le rectangle est un point, c’est‑à‑dire si LLX est égal à URX et LLY est égal à URY. |
| empty | Rectangle vide |
## Méthodes
| Nom | Description |
| :- | :- |
| rotate(angle) | Faire pivoter le rectangle de l’angle spécifié. |
| rotate(angle) | Faire pivoter le rectangle de l’angle spécifié. |
| to_rect() | Convertit le rectangle en instance de System.Drawing.Rectangle. Les positions et la taille en virgule flottante sont tronquées. |
| from_rect(src) | Initialise un nouveau rectangle à partir de l’instance donnée de System.Drawing.Rectangle. |
| parse(value) | Essaye d’analyser la chaîne et d’en extraire les composants du rectangle llx, lly, urx, ury. |
| equals(other) | Vérifie si les rectangles sont égaux, c’est‑à‑dire s’ils ont la même position et les mêmes tailles. |
| near_equals(other, delta) | Vérifie si les rectangles sont presque égaux, c’est‑à‑dire s’ils ont une position et des tailles presque identiques (dans la marge delta). |
| intersect(other_rect) | Intersection de rectangles. |
| join(other_rect) | Joint les rectangles. |
| is_intersect(other_rect) | Détermine si ce rectangle intersecte un autre rectangle. |
| contains(point) | Détermine si le point donné se trouve à l'intérieur du rectangle. |
| center() | Renvoie les coordonnées du centre du rectangle. |
| clone() | Clone l'objet Rectangle. |
| to_points() | Convertit le rectangle en tableau de points ("QuadPoints"). |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

