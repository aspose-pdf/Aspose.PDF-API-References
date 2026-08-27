---
title: "FreeTextAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente une annotation de texte libre qui affiche le texte directement sur la page. Contrairement à une annotation de texte ordinaire, une annotation de texte libre n'a aucun état ouvert ou fermé; au lieu d'être affichée dans une fenêtre contextuelle, le texte est toujours visible."
type: docs
weight: 260
url: /fr/python-net/aspose.pdf.annotations/freetextannotation/
---

## FreeTextAnnotation class

Représente une annotation de texte libre qui affiche le texte directement sur la page. Contrairement à une annotation de texte ordinaire, une annotation de texte libre n'a aucun état ouvert ou fermé; au lieu d'être affichée dans une fenêtre contextuelle, le texte est toujours visible.

Le type FreeTextAnnotation expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| FreeTextAnnotation(document, appearance) | Initialise une nouvelle instance de la classe FreeTextAnnotation |
| FreeTextAnnotation(page, rect, appearance) | Initialise une nouvelle instance de la classe FreeTextAnnotation |
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
| starting_style | Obtient ou définit le style de terminaison de ligne pour le point de terminaison.<br/>            Cette propriété est obsolète, veuillez utiliser EndingStyle. |
| ending_style | Obtient ou définit le style de terminaison de ligne pour le point de terminaison. |
| justification | Obtient ou définit un code spécifiant la forme de justification (quadding) à utiliser pour l'affichage du texte de l'annotation. |
| default_appearance | Obtient ou définit la chaîne d'apparence par défaut à utiliser pour le formatage du texte. |
| default_appearance_object | Objet qui représente l'apparence par défaut de l'annotation FreeText. |
| intent | Obtient ou définit l'intention de l'annotation de texte libre. |
| default_style | Obtient ou définit une chaîne de style par défaut. |
| text_style | Obtient ou définit le style du texte dans l'apparence. Lorsque le style du texte est modifié, l'apparence du texte est mise à jour. |
| tourner | Angle de rotation de l'annotation. |
| annotation d'appel | Tableau de points spécifiant la ligne d'annotation d'appel. |
| text_rectangle | Rectangle décrivant les différences numériques entre deux rectangles : l'entrée Rect de l'annotation<br/>             et un rectangle contenu dans ce rectangle. Le rectangle interne est l'endroit où le texte de l'annotation doit être affiché. |
## Méthodes
| Nom | Description |
| :- | :- |
| clone() | Aucun |
| get_rectangle(consider_rotation) | Renvoie le rectangle de l'annotation en tenant compte de la rotation de la page. |
| accept(visitor) | Accepte un objet visiteur pour traiter l'annotation. |
| flatten() | Place le contenu de l'annotation directement sur la page,<br/>            l'objet d'annotation sera supprimé. |
| change_after_resize(transform) | Met à jour les paramètres et l'apparence, selon la transformation matricielle. |

### Voir aussi

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

