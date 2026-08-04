---
title: "MovieAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente une annotation de film contenant des graphiques animés et du son à présenter sur l'écran d'ordinateur et via les haut-parleurs. Lorsque l'annotation est activée, le film est lu."
type: docs
weight: 480
url: /fr/python-net/aspose.pdf.annotations/movieannotation/
---

## MovieAnnotation class

Représente une annotation de film contenant des graphiques animés et du son à présenter sur l'écran d'ordinateur et via les haut-parleurs. Lorsque l'annotation est activée, le film est lu.

Le type MovieAnnotation expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| MovieAnnotation(document, movie_file) | Initialise une nouvelle instance de la classe MovieAnnotation |
| MovieAnnotation(page, rect, movie_file) | Initialise une nouvelle instance de la classe MovieAnnotation |
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
| title | Obtient ou définit le titre de l'annotation vidéo. |
| file | Obtient ou définit une spécification de fichier identifiant un fichier vidéo auto-descriptif. |
| poster | Obtient ou définit un indicateur ou un flux spécifiant si et comment une image d'affiche représentant la vidéo doit être affichée. Si vrai, l'image d'affiche doit être récupérée du fichier vidéo ; si faux, aucune affiche ne doit être affichée. |
| aspect | Obtient ou définit la largeur et la hauteur de la boîte englobante de la vidéo, en pixels. |
| tourner | Obtient ou définit le nombre de degrés selon lesquels la vidéo doit être pivotée dans le sens des aiguilles d'une montre par rapport à la page. La valeur doit être un multiple de 90. |
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

