---
title: "LinkAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente soit un lien hypertexte vers une destination ailleurs dans le document, soit une action à exécuter."
type: docs
weight: 390
url: /fr/python-net/aspose.pdf.annotations/linkannotation/
---

## LinkAnnotation class

Représente soit un lien hypertexte vers une destination ailleurs dans le document, soit une action à exécuter.

Le type LinkAnnotation expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| LinkAnnotation(page, rect) | Initialise une nouvelle instance de la classe LinkAnnotation |
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
| action | Une action à exécuter lorsque l'annotation de lien est activée. |
| destination | Une destination à afficher lorsque l'annotation est activée. |
| mise en évidence | L'effet visuel à utiliser lorsque le bouton de la souris est pressé ou maintenu enfoncé à l'intérieur de sa zone active. |
## Méthodes
| Nom | Description |
| :- | :- |
| clone() | Clone cette instance.<br/>            Méthode virtuelle. Retourne toujours null. |
| get_rectangle(consider_rotation) | Renvoie le rectangle de l'annotation en tenant compte de la rotation de la page. |
| accept(visitor) | Accepte un objet visiteur pour traiter l'annotation. |
| flatten() | Place le contenu de l'annotation directement sur la page,<br/>            l'objet d'annotation sera supprimé. |
| change_after_resize(transform) | Met à jour les paramètres et l'apparence, selon la transformation matricielle. |

### Voir aussi

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

