---
title: "Font"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente un objet de police."
type: docs
weight: 100
url: /fr/python-net/aspose.pdf.text/font/
---

## Font class

Représente un objet de police.

Le type Font expose les membres suivants :
## Propriétés
| Nom | Description |
| :- | :- |
| font_name | Obtient le nom de police de l'objet [Font](/pdf/python-net/aspose.pdf.text/font/). |
| decoded_font_name | Parfois, les polices PDF (généralement les polices chinoises/japonaises/coréennes) peuvent avoir un nom de police spécifique.<br/>            Ce nom est la valeur de la propriété PDF de police "BaseFont" et parfois cette propriété<br/>            peut être représentée sous forme hexadécimale. Si l'on lit ce nom directement, il peut être affiché<br/>            sous une forme illisible. Pour obtenir une forme lisible, il est nécessaire de décoder le nom de la police selon<br/>            des règles spécifiques à cette police. <br/>            Cette propriété renvoie le nom de police décodé, donc utilisez‑la dans les cas où vous rencontrez <br/>            un [font_name](/pdf/python-net/aspose.pdf.text/font/) illisible.<br/>            Si la propriété [font_name](/pdf/python-net/aspose.pdf.text/font/) a une forme lisible, cette propriété sera identique à <br/>            [font_name](/pdf/python-net/aspose.pdf.text/font/), vous pouvez donc utiliser cette propriété dans tous les cas où vous devez<br/>            obtenir le nom de police sous une forme lisible. |
| base_font | Obtient la valeur BaseFont de l'objet police PDF. Aussi connu sous le nom de nom PostScript de la police. |
| is_embedded | Obtient ou définit une valeur indiquant si la police est incorporée.<br/>            La police basée sur IFont sera automatiquement sous‑ensemble et incorporée |
| is_subset | Obtient ou définit une valeur indiquant si la police est un sous‑ensemble.<br/>             La police basée sur IFont sera automatiquement sous‑ensemble et incorporée |
| is_accessible | Obtient indiquant si la police est présente (installée) dans le système. |
| font_options | Propriétés utiles pour ajuster le comportement de la Font |
## Méthodes
| Nom | Description |
| :- | :- |
| get_last_font_embedding_error() | Le but de cette méthode – renvoyer la description de l’erreur si une tentative<br/>            d’incorporation de police a échoué. S’il n’y a aucun cas d’erreur, elle renvoie une chaîne vide. |
| save(stream) | Enregistre la police dans le flux.<br/>            Notez que la police est enregistrée au format TTF intermédiaire destiné à être utilisé uniquement dans une copie convertie du document original.<br/>            Le fichier de police n’est pas destiné à être utilisé en dehors du contexte du document original. |
| measure_string(str, font_size) | Mesure la chaîne. |

### Voir aussi

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

