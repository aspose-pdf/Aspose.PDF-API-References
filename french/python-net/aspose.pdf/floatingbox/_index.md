---
title: "FloatingBox"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: 
type: docs
weight: 370
url: /fr/python-net/aspose.pdf/floatingbox/
---

## FloatingBox class



Le type FloatingBox expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| FloatingBox(width, height) | Initialise une nouvelle instance de la classe FloatingBox |
| FloatingBox() | Initialise une nouvelle instance de la classe [FloatingBox](/pdf/python-net/aspose.pdf/floatingbox/). |
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
| column_info | Obtient ou définit les informations d'une colonne |
| largeur | Obtient ou définit une valeur flottante qui indique la largeur de la boîte flottante. |
| hauteur | Obtient ou définit une valeur flottante qui indique la hauteur de la boîte flottante. |
| is_need_repeating | Obtient ou définit une valeur booléenne qui indique si le paragraphe doit être répété sur la page suivante.<br/>            La valeur par défaut est false. L'attribut n'est valide que lorsque le paragraphe lui‑-même et l'objet auquel son ReferenceParagraphID fait référence sont tous deux inclus dans RepeatingRows. |
| paragraphs | Obtient ou définit une collection de [paragraphs](/pdf/python-net/aspose.pdf/floatingbox/) qui indique tous les paragraphes de la cellule. |
| border | Obtient ou définit un objet [BorderInfo](/pdf/python-net/aspose.pdf/borderinfo/) qui indique les informations de bordure de la boîte flottante. |
| background_color | Obtient ou définit un objet [Color](/pdf/python-net/aspose.pdf/color/) qui indique la couleur d'arrière‑plan de la boîte flottante. |
| background_image | Obtient ou définit l'image d'arrière‑plan de la page (uniquement pour le générateur, non remplie lors de la lecture du document). |
| padding | Obtient ou définit un objet [MarginInfo](/pdf/python-net/aspose.pdf/margininfo/) qui indique le remplissage de la boîte flottante. |
| left | Obtient ou définit la coordonnée gauche du tableau. |
| top | Obtient ou définit la coordonnée supérieure du tableau. |
## Méthodes
| Nom | Description |
| :- | :- |
| clone() | Clone un nouvel objet [FloatingBox](/pdf/python-net/aspose.pdf/floatingbox/). Les paragraphes dans la boîte flottante ne sont pas clonés. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

