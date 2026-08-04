---
title: "HtmlFragment"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente un fragment html."
type: docs
weight: 470
url: /fr/python-net/aspose.pdf/htmlfragment/
---

## HtmlFragment class

Représente un fragment html.

Le type HtmlFragment expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| HtmlFragment(text) | Initialise une nouvelle instance de la classe HtmlFragment |
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
| rectangle | Obtient le rectangle du HtmlFragment |
| is_paragraph_has_margin | Obtient ou définit si le paragraphe a une marge par défaut, sinon la marge est 0 |
| is_break_words | Obtient ou définit la coupure des mots |
| text_state | Obtient ou définit la police |
| html_load_options | Obtient ou définit les HtmlLoadOptions qui seront utilisés pour le chargement (et le rendu) du HTML dans cette instance de classe.<br/>            Veuillez l'utiliser lorsqu'il est nécessaire d'utiliser un paramètre spécifique pour l'importation du HTML pour telle ou telle instance<br/>             (par ex. lorsque cette instance ou cette autre doit utiliser un BasePath spécifique pour le HTML importé ou doit utiliser un chargeur spécifique de ressources externes)<br/>            Si le paramètre est par défaut (null), alors les options de chargement HTML standard seront utilisées. |
## Méthodes
| Nom | Description |
| :- | :- |
| clone() | Clone le fragment HTML. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

