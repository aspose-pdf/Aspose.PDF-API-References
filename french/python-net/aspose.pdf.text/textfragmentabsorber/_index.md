---
title: "TextFragmentAbsorber"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente un objet absorbeur de fragments de texte.<br/>            Effectue la recherche de texte et fournit l'accès aux résultats de recherche via la collection [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/)."
type: docs
weight: 400
url: /fr/python-net/aspose.pdf.text/textfragmentabsorber/
---

## TextFragmentAbsorber class

Représente un objet absorbeur de fragments de texte.<br/>            Effectue la recherche de texte et fournit l'accès aux résultats de recherche via la collection [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/).

Le type TextFragmentAbsorber expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| TextFragmentAbsorber() | Initialise une nouvelle instance du [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) qui effectue la recherche de tous les segments de texte du document ou de la page. |
| TextFragmentAbsorber(text_edit_options) | Initialise une nouvelle instance de la classe TextFragmentAbsorber |
| TextFragmentAbsorber(phrase) | Initialise une nouvelle instance de la classe TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_search_options) | Initialise une nouvelle instance de la classe TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_search_options, text_edit_options) | Initialise une nouvelle instance de la classe TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_edit_options) | Initialise une nouvelle instance de la classe TextFragmentAbsorber |
## Propriétés
| Nom | Description |
| :- | :- |
| text | Obtient le texte extrait que le [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) extrait du document ou de la page PDF. |
| has_errors | La valeur indique si des erreurs ont été trouvées lors de l'extraction du texte.<br/>            La recherche d'erreurs ne sera effectuée que si TextSearchOptions.LogTextExtractionErrors = true ; et cela peut diminuer les performances. |
| errors | Liste d'objets [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/). Elle contient des informations sur les erreurs trouvées lors de l'extraction du texte.<br/>            La recherche d'erreurs ne sera effectuée que si TextSearchOptions.LogTextExtractionErrors = true ; et cela peut diminuer les performances. |
| extraction_options | Obtient ou définit les options d'extraction de texte. |
| text_search_options | Obtient ou définit les options de recherche. Les options permettent la recherche à l'aide d'expressions régulières. |
| text_fragments | Obtient la collection d'occurrences de recherche présentées avec des objets [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| phrase | Obtient ou définit la phrase que le [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) recherche dans le document PDF ou la page. |
| text_edit_options | Obtient ou définit les options de modification de texte. Les options définissent un comportement spécial lorsque le symbole demandé ne peut pas être écrit avec la police. |
| text_replace_options | Obtient ou définit les options de remplacement de texte. Les options définissent le comportement lorsque le texte du fragment est remplacé par un texte plus court ou plus long. |
## Méthodes
| Nom | Description |
| :- | :- |
| visit(page) | Effectue une recherche sur la page spécifiée. |
| visit(pdf) | Effectue une recherche sur le document spécifié. |
| visit(x_form) | Effectue une recherche sur l'objet de formulaire spécifié. |
| apply_for_all_fragments(font) | Applique la police à tous les fragments de texte qui ont été absorbés. Cela fonctionne plus rapidement que de parcourir les fragments si tous les fragments sur la ou les pages ont été absorbés. Sinon, cela fonctionne de manière similaire au parcours. |
| apply_for_all_fragments(font_size) | Applique la taille de police à tous les fragments de texte qui ont été absorbés. Cela fonctionne plus rapidement que de parcourir les fragments si tous les fragments sur la ou les pages ont été absorbés. Sinon, cela fonctionne de manière similaire au parcours. |
| apply_for_all_fragments(font, font_size) | Applique la police et la taille à tous les fragments de texte qui ont été absorbés. Cela fonctionne plus rapidement que de parcourir les fragments si tous les fragments sur la ou les pages ont été absorbés. Sinon, cela fonctionne de manière similaire au parcours. |
| remove_all_text(page) | Supprime tout le texte de la page spécifiée. |
| remove_all_text(page, rect) | Supprime le texte à l'intérieur du rectangle spécifié de la page spécifiée. |
| remove_all_text(document) | Supprime tout le texte du document. |
| reset() | Efface la collection TextFragments de cet objet [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/). |

### Voir aussi

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

