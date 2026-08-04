---
title: "MarkupParagraph"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente un paragraphe."
type: docs
weight: 200
url: /fr/python-net/aspose.pdf.text/markupparagraph/
---

## MarkupParagraph class

Représente un paragraphe.

Le type MarkupParagraph expose les membres suivants :
## Propriétés
| Nom | Description |
| :- | :- |
| points | Points du polygone qui décrit le paragraphe.<br/>            Le point de départ est le coin inférieur gauche du paragraphe. Et les points suivants sont dans le sens anti-horaire. |
| secondary_points | Points du polygone secondaire qui décrit la continuation du paragraphe. Il ne sera pas nul si le paragraphe se poursuit dans la colonne ou la page suivante.<br/>            Le point de départ est le coin inférieur gauche du paragraphe. Et les points suivants sont dans le sens anti-horaire. |
| continuation_page_numbers | Liste des numéros de page sur lesquels le paragraphe se poursuit. Elle correspondra à la page où le paragraphe a commencé s'il continue dans la colonne suivante de la même page. |
| fragments | Collection d'objets [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) non vides du paragraphe. |
| lines | Lignes du paragraphe. Chaque ligne est représentée par une liste de fragments de texte. |
| text | Obtient l'objet texte chaîne que représente l'objet [MarkupParagraph](/pdf/python-net/aspose.pdf.text/markupparagraph/). |

### Voir aussi

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

