---
title: "FitRExplicitDestination"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente une destination explicite qui affiche la page avec son contenu agrandi juste assez pour que le rectangle spécifié par les coordonnées left, bottom, right et top tienne entièrement dans la fenêtre, à la fois horizontalement et verticalement. Si les facteurs d'agrandissement horizontal et vertical requis sont différents, utilisez le plus petit des deux, en centrant le rectangle dans la fenêtre dans l'autre dimension. Une valeur null pour l'un des paramètres peut entraîner un comportement imprévisible."
type: docs
weight: 230
url: /fr/python-net/aspose.pdf.annotations/fitrexplicitdestination/
---

## FitRExplicitDestination class

Représente une destination explicite qui affiche la page avec son contenu agrandi juste assez pour que le rectangle spécifié par les coordonnées left, bottom, right et top tienne entièrement dans la fenêtre, à la fois horizontalement et verticalement. Si les facteurs d'agrandissement horizontal et vertical requis sont différents, utilisez le plus petit des deux, en centrant le rectangle dans la fenêtre dans l'autre dimension. Une valeur null pour l'un des paramètres peut entraîner un comportement imprévisible.

Le type FitRExplicitDestination expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| FitRExplicitDestination(page, left, bottom, right, top) | Initialise une nouvelle instance de la classe FitRExplicitDestination |
| FitRExplicitDestination(document, page_number, left, bottom, right, top) | Initialise une nouvelle instance de la classe FitRExplicitDestination |
| FitRExplicitDestination(page_number, left, bottom, right, top) | Initialise une nouvelle instance de la classe FitRExplicitDestination |
## Propriétés
| Nom | Description |
| :- | :- |
| page | Obtient l'objet de la page de destination |
| page_number | Obtient le numéro de page de destination |
| left | Obtient la coordonnée horizontale gauche du rectangle visible. |
| bottom | Obtient la coordonnée verticale inférieure du rectangle visible. |
| droite | Obtient la coordonnée horizontale droite du rectangle visible. |
| top | Obtient la coordonnée verticale supérieure du rectangle visible. |
## Méthodes
| Nom | Description |
| :- | :- |
| create_destination(page, type, values) | Crée des instances des classes dérivées d'ExplicitDestination. |
| create_destination(doc, page_number, type, values) | Crée des instances des classes dérivées d'ExplicitDestination. |
| create_destination(page_number, type, values) | Crée des instances des classes dérivées d'ExplicitDestination. |
| to_string() | Convertit l'état de l'objet en valeur chaîne. Exemple: "1 FitR 100 200 300 400". |

### Voir aussi

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

