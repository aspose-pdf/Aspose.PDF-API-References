---
title: "LineAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Classe représentant l'annotation de ligne."
type: docs
weight: 380
url: /fr/python-net/aspose.pdf.annotations/lineannotation/
---

## LineAnnotation class

Classe représentant l'annotation de ligne.

Le type LineAnnotation expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| LineAnnotation(document, start, end) | Initialise une nouvelle instance de la classe LineAnnotation |
| LineAnnotation(page, rect, start, end) | Initialise une nouvelle instance de la classe LineAnnotation |
## Propriétés
| Nom | Description |
| :- | :- |
| vertical_alignment | Aucun |
| horizontal_alignment | Obtient ou définit l'alignement du texte pour l'annotation. |
| marge | Aucun |
| is_first_paragraph_in_column | Aucun |
| is_kept_with_next | Aucun |
| is_in_new_page | Aucun |
| is_in_line_paragraph | Aucun |
| hyperlien | Aucun |
| z_index | Aucun |
| mettre_a_jour_apparence_a_la_conversion | Si vrai, l'apparence de l'annotation sera mise à jour avant de convertir le document PF en image. Cela permet de convertir correctement les champs mais demande probablement plus de temps. |
| utiliser_sous_ensemble_de_police | Si cette propriété est définie sur true, les polices seront ajoutées au document sous forme de sous-ensembles. La valeur par défaut est true. |
| drapeaux | Drapeaux de l'annotation. |
| type_annotation | Obtient le type de l'annotation. |
| largeur | Obtient ou définit la largeur de l'annotation. |
| actions | Obtient la liste des actions d'annotation. |
| hauteur | Obtient ou définit la hauteur de l'annotation. |
| rect | Obtient ou définit le rectangle d'annotation. |
| contenu | Obtient ou définit le texte de l'annotation. |
| nom | Obtient ou définit le nom de l'annotation sur la page. |
| modifié | Obtient ou définit la date et l'heure de la dernière modification de l'annotation. |
| couleur | Obtient ou définit la couleur de l'annotation. |
| border | Obtient ou définit les caractéristiques de la bordure de l'annotation. [border](/pdf/python-net/aspose.pdf.annotations/annotation/) |
| etat_actif | Obtient ou définit l'état d'apparence de l'annotation actuelle. |
| caractéristiques | Obtient les caractéristiques de l'annotation. |
| états | Obtient le dictionnaire d'apparence de l'annotation. |
| alignement | Alignement de l'annotation. Cette propriété est obsolète. Utilisez HorizontalAligment à la place. |
| alignement_horizontal_texte | Obtient ou définit l'alignement du texte pour l'annotation. |
| nom_complet | Obtient le nom complet de l'annotation. |
| apparence | Obtient le dictionnaire d'apparence de l'annotation. |
| indice_page | Obtient l'index de la page contenant l'annotation. |
| title | Obtient ou définit le texte qui doit être affiché dans la barre de titre de l'annotation. |
| rich_text | Obtient ou définit une chaîne de texte enrichi à afficher dans la fenêtre contextuelle lorsque l'annotation est ouverte. |
| creation_date | Obtient la date et l'heure de création de l'annotation. |
| subject | Obtient le texte représentant la description de l'objet. |
| popup | Annotation contextuelle pour saisir ou modifier le texte associé à cette annotation. |
| opacité | Obtient ou définit la valeur d'opacité constante à utiliser lors du rendu de l'annotation. |
| in_reply_to | Une référence à l'annotation à laquelle cette annotation répond.<br/>            Les deux annotations doivent se trouver sur la même page du document. |
| reply_type | Une chaîne spécifiant la relation (le \"type de réponse\") entre cette annotation<br/>            et celle spécifiée par InReplyTo. |
| début | Obtient ou définit le point de départ de la ligne. |
| starting_style | Obtient ou définit le style de terminaison de ligne pour le point de départ de la ligne. |
| terminaison | Obtient ou définit le point de terminaison de la ligne. |
| ending_style | Obtient ou définit le style de terminaison pour le point final de la ligne. |
| interior_color | Obtient ou définit la couleur intérieure de l'annotation. |
| leader_line | Obtient ou définit la longueur de la ligne directrice. |
| leader_line_extension | Obtient ou définit la longueur de l'extension de la ligne directrice. |
| show_caption | Obtient ou définit le drapeau booléen qui détermine si le contenu doit être affiché comme légende. |
| leader_line_offset | Obtient ou définit le décalage de la ligne directrice. |
| caption_offset | Obtient ou définit le décalage du texte de la légende par rapport à sa position normale. |
| caption_position | Obtient ou définit la position de la légende de l'annotation. |
| mesure | Unités de mesure spécifiées pour cette annotation. |
| intent | Obtient ou définit l'intention de l'annotation de ligne. |
## Méthodes
| Nom | Description |
| :- | :- |
| clone() | Aucun |
| get_rectangle(consider_rotation) | Renvoie le rectangle de l'annotation en tenant compte de la rotation de la page. |
| accept(visitor) | Accepte un visiteur pour le traitement de l'annotation. |
| flatten() | Place le contenu de l'annotation directement sur la page,<br/>            l'objet d'annotation sera supprimé. |
| change_after_resize(transform) | Met à jour les points de départ et d'arrivée, selon la transformation matricielle. |

### Voir aussi

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

