---
title: "Graph"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente le graphe - paragraphe du générateur graphique."
type: docs
weight: 70
url: /fr/python-net/aspose.pdf.drawing/graph/
---

## Graph class

Représente le graphe - paragraphe du générateur graphique.

Le type Graph expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| Graph(width, height) | Initialise une nouvelle instance de la classe Graph |
## Propriétés
| Nom | Description |
| :- | :- |
| vertical_alignment | Obtient ou définit un alignement vertical du paragraphe |
| horizontal_alignment | Obtient ou définit un alignement horizontal du paragraphe |
| marge | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de PDF) |
| is_first_paragraph_in_column | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante.<br/>            La valeur par défaut est false. (pour la génération de PDF) |
| is_kept_with_next | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page avec le paragraphe suivant.<br/>            La valeur par défaut est false. (pour la génération de PDF) |
| is_in_new_page | Obtient ou définit une valeur booléenne qui force ce paragraphe à se générer sur une nouvelle page.<br/>            La valeur par défaut est false. (pour la génération de PDF) |
| is_in_line_paragraph | Obtient ou définit si un paragraphe est en ligne.<br/>            La valeur par défaut est false. (pour la génération de PDF) |
| hyperlien | Obtient ou définit le lien hypertexte du fragment (pour le générateur de PDF). |
| z_index | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand <br/>            sera placé au-dessus du graphique avec un ZIndex plus petit. Le ZIndex peut être négatif. Un graphique avec un ZIndex négatif <br/>            sera placé derrière le texte de la page. |
| graph_info | Obtient ou définit un objet [graph_info](/pdf/python-net/aspose.pdf.drawing/graph/) qui indique les informations du graphique, telles que la couleur,<br/>            la largeur de ligne, etc. |
| bordure | Obtient ou définit la bordure. |
| is_change_position | Obtient ou définit le changement de position actuelle après le traitement du paragraphe. (par défaut true) |
| left | Obtient ou définit la coordonnée gauche du tableau. |
| top | Obtient ou définit la coordonnée supérieure du tableau. |
| shapes | Obtient ou définit une collection [shapes](/pdf/python-net/aspose.pdf.drawing/graph/) qui indique toutes les formes du graphique. |
| title | Obtient ou définit une valeur chaîne qui indique le titre du graphique. |
| largeur | Obtient ou définit une valeur float qui indique la largeur du graphique.<br/>            L'unité est le point. |
| hauteur | Obtient ou définit une valeur float qui indique la hauteur du graphique.<br/>            L'unité est le point. |
## Méthodes
| Nom | Description |
| :- | :- |
| clone() | Clone le graphique. |

### Voir aussi

* namespace [aspose.pdf.drawing](/pdf/python-net/aspose.pdf.drawing/)
* assembly [Aspose.PDF](/pdf/python-net/)

