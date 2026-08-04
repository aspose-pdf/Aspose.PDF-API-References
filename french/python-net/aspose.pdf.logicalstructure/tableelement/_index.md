---
title: "TableElement"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente l'élément de structure Table dans la structure logique."
type: docs
weight: 610
url: /fr/python-net/aspose.pdf.logicalstructure/tableelement/
---

## TableElement class

Représente l'élément de structure Table dans la structure logique.

Le type TableElement expose les membres suivants :
## Propriétés
| Nom | Description |
| :- | :- |
| parent_element | Aucun |
| child_elements | Aucun |
| default_attribute_owner | Obtient |
| attributs | Obtient |
| structure_type | Obtient le type de l'élément de structure. |
| id | Obtient l'ID de l'élément de structure. |
| title | Obtient ou définit le titre de l'élément de structure. |
| language | Obtient ou définit la langue de l'élément de structure. |
| alternative_text | Obtient ou définit le texte alternatif de l'élément de structure. |
| expansion_text | Obtient ou définit le texte d'expansion de l'élément de structure. |
| actual_text | Obtient ou définit le texte réel de l'élément de structure. |
| background_color | Obtient ou définit la couleur d'arrière-plan du tableau. |
| bordure | Obtient ou définit la bordure du tableau. |
| alignement | Obtient ou définit l'alignement du tableau. |
| corner_style | Obtient ou définit les styles des coins de la bordure |
| broken | Obtient ou définit le tableau vertical cassé; |
| column_adjustment | Obtient ou définit l'ajustement des colonnes du tableau. |
| column_widths | Obtient les largeurs des colonnes du tableau. |
| default_cell_border | Obtient la bordure de cellule par défaut. |
| default_cell_padding | Obtient ou définit le remplissage de cellule par défaut. |
| default_cell_text_state | Obtient ou définit l'état de texte par défaut de la cellule. |
| default_column_width | Obtient ou définit la largeur de colonne par défaut. |
| is_broken | Obtient ou définit si le tableau est cassé - sera tronqué pour la page suivante. |
| is_borders_included | Obtient ou définit la bordure incluse dans les largeurs de colonne. |
| left | Obtient ou définit la coordonnée gauche du tableau. |
| top | Obtient ou définit la coordonnée supérieure du tableau. |
| repeating_columns_count | Obtient ou définit le nombre maximal de colonnes pour le tableau. |
| repeating_rows_count | Obtient le nombre de premières lignes répétées sur plusieurs pages. |
| repeating_rows_style | Obtient le style des lignes répétées. |
## Méthodes
| Nom | Description |
| :- | :- |
| append_child(element) | Aucun |
| change_parent_element(new_parent_element) | Modifier l'élément parent pour l'élément de structure actuel |
| generate_id() | Générer l'ID pour l'élément de structure. |
| set_id(id) | Définit l'ID pour l'élément de structure. |
| clear_id() | Efface l'ID pour l'élément de structure. |
| set_tag(new_tag) | Définit une balise personnalisée pour l'élément de structure. |
| create_t_head() | Crée [TableTHeadElement](/pdf/python-net/aspose.pdf.logicalstructure/tabletheadelement/) et l'ajoute au tableau actuel. |
| create_t_body() | Crée [TableTHeadElement](/pdf/python-net/aspose.pdf.logicalstructure/tabletheadelement/) et l'ajoute au tableau actuel. |
| create_t_foot() | Crée [TableTFootElement](/pdf/python-net/aspose.pdf.logicalstructure/tabletfootelement/) et l'ajoute au tableau actuel. |

### Voir aussi

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

