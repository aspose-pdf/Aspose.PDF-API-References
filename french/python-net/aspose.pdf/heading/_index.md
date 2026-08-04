---
title: "Heading"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente l'en-tête."
type: docs
weight: 460
url: /fr/python-net/aspose.pdf/heading/
---

## Heading class

Représente l'en-tête.

Le type Heading expose les membres suivants:
## Constructeurs
| Nom | Description |
| :- | :- |
| Heading(level) | Initialise une nouvelle instance de la classe Heading |
## Propriétés
| Nom | Description |
| :- | :- |
| vertical_alignment | Obtient ou définit un alignement vertical du fragment de texte. |
| horizontal_alignment | Obtient ou définit un alignement horizontal du fragment de texte. |
| marge | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de PDF) |
| is_first_paragraph_in_column | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante.<br/>            La valeur par défaut est false. (pour la génération de PDF) |
| is_kept_with_next | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page avec le paragraphe suivant.<br/>            La valeur par défaut est false. (pour la génération de PDF) |
| is_in_new_page | Obtient ou définit une valeur booléenne qui force ce paragraphe à se générer sur une nouvelle page.<br/>            La valeur par défaut est false. (pour la génération de PDF) |
| is_in_line_paragraph | Obtient ou définit si un paragraphe est en ligne.<br/>            La valeur par défaut est false. (pour la génération de PDF) |
| hyperlien | Définit le lien hypertexte du fragment |
| z_index | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand <br/>            sera placé au-dessus du graphique avec un ZIndex plus petit. Le ZIndex peut être négatif. Un graphique avec un ZIndex négatif <br/>            sera placé derrière le texte de la page. |
| replace_options | Obtient les options de remplacement de texte. Les options définissent le comportement lorsque le texte du fragment est remplacé par un texte plus court ou plus long. |
| text | Obtient ou définit l'objet texte chaîne que représente l'objet [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| text_state | Obtient ou définit l'état du texte pour le texte que représente l'objet [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| segments | Obtient les segments de texte pour le [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) actuel. |
| position | Obtient ou définit la position du texte pour le texte, représenté par l'objet [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| baseline_position | Obtient la position du texte pour le texte, représenté par l'objet [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/).<br/>            Le YIndent de la structure Position représente la coordonnée de la ligne de base du fragment de texte. |
| rectangle | Obtient le rectangle du TextFragment |
| page | Obtient la page qui contient le TextFragment |
| form | Obtient l'objet de formulaire qui contient le TextFragment |
| wrap_lines_count | Obtient ou définit le nombre de lignes d'enroulement pour ce paragraphe(pour la génération de PDF uniquement) |
| end_note | Obtient ou définit la note de fin du paragraphe.(pour la génération de PDF uniquement) |
| foot_note | Obtient ou définit la note de bas de page du paragraphe.(pour la génération de PDF uniquement) |
| toc_page | Obtient la page qui contient cet en‑tête. |
| top | Obtient le Y supérieur de ces en‑têtes. |
| start_number | Obtient le numéro de départ de l’en‑tête. |
| is_auto_sequence | Obtient si l’en‑tête doit être numéroté automatiquement. |
| is_in_list | Obtient si l’en‑tête doit être dans la liste de la table des matières. |
| destination_page | Obtient la page de destination. |
| niveau | Obtient le niveau. |
| style | Obtient ou définit le style. |
| user_label | Obtient ou définit le libellé utilisateur. |
## Méthodes
| Nom | Description |
| :- | :- |
| clone() | Clone l’en‑tête. |
| isolate_text_segments(start_index, length) | Obtient les [TextSegment](/pdf/python-net/aspose.pdf.text/textsegment/)(s) représentant la partie spécifiée du texte du [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| clone_with_segments() | Clone l’en‑tête avec tous les segments. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

