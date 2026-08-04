---
title: "Table"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente un tableau qui peut être ajouté à la page."
type: docs
weight: 1480
url: /fr/python-net/aspose.pdf/table/
---

## Table class

Représente un tableau qui peut être ajouté à la page.

Le type Table expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| Table() | Initialise une nouvelle instance de la classe Table |
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
| background_color | Obtient ou définit la couleur de fond du tableau |
| break_text | Obtient ou définit le texte de rupture pour le tableau |
| corner_style | Obtient ou définit les styles des coins de la bordure |
| repeating_rows_style | Obtient le style pour les lignes répétées |
| repeating_columns_count | Obtient ou définit le nombre maximal de colonnes pour le tableau |
| repeating_rows_count | Obtient le nombre de premières lignes répétées sur plusieurs pages |
| column_widths | Obtient les largeurs des colonnes du tableau. |
| broken | Obtient ou définit le tableau vertical cassé; |
| default_cell_border | Obtient la bordure de cellule par défaut ; |
| default_column_width | Obtient la bordure de cellule par défaut ; |
| lignes | Obtient les lignes du tableau. |
| bordure | Obtient ou définit la bordure. |
| default_cell_padding | Obtient ou définit le remplissage de cellule par défaut. |
| default_cell_text_state | Obtient ou définit l'état de texte par défaut de la cellule. |
| alignement | Obtient ou définit l'alignement du tableau. |
| left | Obtient ou définit la coordonnée gauche du tableau. |
| top | Obtient ou définit la coordonnée supérieure du tableau. |
| is_broken | Obtient ou définit si le tableau est cassé - sera tronqué pour la page suivante. |
| is_borders_included | Obtient ou définit la bordure incluse dans les largeurs de colonne. |
| column_adjustment | Obtient ou définit l'ajustement des colonnes du tableau. |
## Méthodes
| Nom | Description |
| :- | :- |
| clone() | Clone le tableau. |
| get_width() | Obtenir la largeur. |
| get_height(parent_page) | Obtenir la hauteur. |
| set_column_text_state(col_number, text_state) | Définir la hauteur. |
| import_array(imported_array, first_filled_row, first_filled_column, is_left_columns_filled) | Importe un tableau unidimensionnel de données dans le tableau. L'importation place une cellule pour chaque élément du tableau et<br/>              commence à la ligne et à la colonne définies dans les paramètres. Pendant l'importation, si l'on détecte que les lignes nécessaires<br/>              sont encore absentes (c.-à-d. que le tableau cible est trop petit pour absorber toutes les données), les lignes nécessaires seront créées |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

