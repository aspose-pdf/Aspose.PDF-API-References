---
title: "XYZExplicitDestination"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente une destination explicite qui affiche la page avec les coordonnées (gauche, haut) positionnées dans le coin supérieur gauche de la fenêtre et le contenu de la page agrandi par le facteur de zoom. Une valeur nulle pour l'un des paramètres gauche, haut ou zoom indique que la valeur actuelle de ce paramètre doit être conservée telle quelle. Une valeur de zoom de 0 a le même sens qu'une valeur nulle."
type: docs
weight: 880
url: /fr/python-net/aspose.pdf.annotations/xyzexplicitdestination/
---

## XYZExplicitDestination class

Représente une destination explicite qui affiche la page avec les coordonnées (gauche, haut) positionnées dans le coin supérieur gauche de la fenêtre et le contenu de la page agrandi par le facteur de zoom. Une valeur nulle pour l'un des paramètres gauche, haut ou zoom indique que la valeur actuelle de ce paramètre doit être conservée telle quelle. Une valeur de zoom de 0 a le même sens qu'une valeur nulle.

Le type XYZExplicitDestination expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| XYZExplicitDestination(page, left, top, zoom) | Initialise une nouvelle instance de la classe XYZExplicitDestination |
| XYZExplicitDestination(document, page_number, left, top, zoom) | Initialise une nouvelle instance de la classe XYZExplicitDestination |
| XYZExplicitDestination(page_number, left, top, zoom) | Initialise une nouvelle instance de la classe XYZExplicitDestination |
## Propriétés
| Nom | Description |
| :- | :- |
| page | Obtient l'objet de la page de destination |
| page_number | Obtient le numéro de page de destination |
| left | Obtient la coordonnée horizontale gauche du coin supérieur gauche de la fenêtre. |
| top | Obtient la coordonnée verticale supérieure du coin supérieur gauche de la fenêtre. |
| zoom | Obtient le facteur de zoom. |
## Méthodes
| Nom | Description |
| :- | :- |
| create_destination(page, left, top, zoom, consider_rotation) | Créer la destination à l'emplacement spécifié de la page en tenant compte de la rotation de la page si nécessaire. |
| create_destination(page, type, values) | Crée des instances des classes dérivées d'ExplicitDestination. |
| create_destination(doc, page_number, type, values) | Crée des instances des classes dérivées d'ExplicitDestination. |
| create_destination(page_number, type, values) | Crée des instances des classes dérivées d'ExplicitDestination. |
| create_destination_to_upper_left_corner(page, zoom) | Créer la destination au coin supérieur gauche de la page spécifiée. |
| create_destination_to_upper_left_corner(page) | Créer la destination au coin supérieur gauche de la page spécifiée. |
| to_string() | Convertit l'état de l'objet en valeur chaîne. Exemple : "1 XYZ 100 200 3". |

### Voir aussi

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

