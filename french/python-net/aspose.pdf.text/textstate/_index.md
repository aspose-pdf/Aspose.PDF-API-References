---
title: "TextState"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente l'état d'un texte"
type: docs
weight: 490
url: /fr/python-net/aspose.pdf.text/textstate/
---

## TextState class

Représente l'état d'un texte

Le type TextState expose les membres suivants:
## Constructeurs
| Nom | Description |
| :- | :- |
| TextState() | Crée un objet d'état de texte. |
| TextState(font_size) | Initialise une nouvelle instance de la classe TextState |
| TextState(foreground_color) | Initialise une nouvelle instance de la classe TextState |
| TextState(foreground_color, font_size) | Initialise une nouvelle instance de la classe TextState |
| TextState(font_family) | Initialise une nouvelle instance de la classe TextState |
| TextState(font_family, bold, italic) | Initialise une nouvelle instance de la classe TextState |
| TextState(font_family, font_size) | Initialise une nouvelle instance de la classe TextState |
## Propriétés
| Nom | Description |
| :- | :- |
| character_spacing | Obtient ou définit l'espacement des caractères du texte. |
| line_spacing | Obtient ou définit l'espacement des lignes du texte. |
| horizontal_scaling | Obtient ou définit le redimensionnement horizontal du texte. |
| subscript | Obtient ou définit l'indice du texte. |
| superscript | Obtient ou définit l'exposant du texte. |
| word_spacing | Obtient ou définit l'espacement des mots du texte. |
| invisible | Obtient ou définit l'invisibilité du texte. Cela reflète essentiellement l'état [rendering_mode](/pdf/python-net/aspose.pdf.text/textstate/), sauf dans certains cas particuliers (comme le rognage). |
| rendering_mode | Obtient ou définit le mode de rendu du texte. |
| font_size | Obtient ou définit la taille de police du texte. |
| font | Obtient ou définit la police du texte. |
| foreground_color | Obtient ou définit la couleur de premier plan du texte. |
| stroking_color | Obtient ou définit la couleur de premier plan du texte. |
| underline | Obtient ou définit le soulignement du texte, représenté par l'objet [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) |
| strike_out | Définit le texte barré, représenté par l'objet [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) |
| background_color | Définit la couleur d'arrière-plan du texte. |
| font_style | Définit le style de police du texte. |
| horizontal_alignment | Obtient ou définit l'alignement horizontal du texte. |
| TAB_TAG | Vous pouvez placer cette balise dans le texte pour déclarer une tabulation. |
| TABSTOP_DEFAULT_VALUE | Valeur par défaut de la tabulation dans les largeurs du caractère espace de la police par défaut. |
## Méthodes
| Nom | Description |
| :- | :- |
| apply_changes_from(text_state) | Applique les paramètres d'un autre textState. |
| measure_string(str) | Mesure la chaîne. |

### Voir aussi

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

