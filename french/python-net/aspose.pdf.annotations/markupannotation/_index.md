---
title: "MarkupAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Classe abstraite représentant l'annotation de balisage."
type: docs
weight: 400
url: /fr/python-net/aspose.pdf.annotations/markupannotation/
---

## MarkupAnnotation class

Classe abstraite représentant l'annotation de balisage.

Le type MarkupAnnotation expose les membres suivants :
## Propriétés
| Nom | Description |
| :- | :- |
| vertical_alignment | Obtient ou définit un alignement vertical du paragraphe |
| horizontal_alignment | Obtient ou définit l'alignement du texte pour l'annotation. |
| marge | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de PDF) |
| is_first_paragraph_in_column | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante.<br/>            La valeur par défaut est false. (pour la génération de PDF) |
| is_kept_with_next | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page avec le paragraphe suivant.<br/>            La valeur par défaut est false. (pour la génération de PDF) |
| is_in_new_page | Obtient ou définit une valeur booléenne qui force ce paragraphe à se générer sur une nouvelle page.<br/>            La valeur par défaut est false. (pour la génération de PDF) |
| is_in_line_paragraph | Obtient ou définit si un paragraphe est en ligne.<br/>            La valeur par défaut est false. (pour la génération de PDF) |
| hyperlien | Obtient ou définit le lien hypertexte du fragment (pour le générateur de PDF). |
| z_index | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand <br/>            sera placé au-dessus du graphique avec un ZIndex plus petit. Le ZIndex peut être négatif. Un graphique avec un ZIndex négatif <br/>            sera placé derrière le texte de la page. |
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
## Méthodes
| Nom | Description |
| :- | :- |
| clone() | Clone cette instance.<br/>            Méthode virtuelle. Retourne toujours null. |
| get_rectangle(consider_rotation) | Renvoie le rectangle de l'annotation en tenant compte de la rotation de la page. |
| accept(visitor) | Accepte un visiteur pour le traitement de l'annotation. |
| flatten() | Place le contenu de l'annotation directement sur la page,<br/>            l'objet d'annotation sera supprimé. |
| change_after_resize(transform) | Met à jour les paramètres et l'apparence, selon la transformation matricielle. |

### Voir aussi

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

