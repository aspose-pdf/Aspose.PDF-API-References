---
title: "TextAbsorber"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente un objet absorbeur d'un texte.<br/>            Effectue l'extraction de texte et fournit l'accès au résultat via l'objet [text](/pdf/python-net/aspose.pdf.text/textabsorber/)."
type: docs
weight: 320
url: /fr/python-net/aspose.pdf.text/textabsorber/
---

## TextAbsorber class

Représente un objet absorbeur d'un texte.<br/>            Effectue l'extraction de texte et fournit l'accès au résultat via l'objet [text](/pdf/python-net/aspose.pdf.text/textabsorber/).

Le type TextAbsorber expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| TextAbsorber() | Initialise une nouvelle instance de [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/). |
| TextAbsorber(extraction_options) | Initialise une nouvelle instance de la classe TextAbsorber |
| TextAbsorber(extraction_options, text_search_options) | Initialise une nouvelle instance de la classe TextAbsorber |
| TextAbsorber(text_search_options) | Initialise une nouvelle instance de la classe TextAbsorber |
## Propriétés
| Nom | Description |
| :- | :- |
| text | Obtient le texte extrait que le [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) extrait du document ou de la page PDF. |
| has_errors | La valeur indique si des erreurs ont été trouvées lors de l'extraction du texte.<br/>            La recherche d'erreurs ne sera effectuée que si TextSearchOptions.LogTextExtractionErrors = true ; et cela peut diminuer les performances. |
| errors | Liste d'objets [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/). Elle contient des informations sur les erreurs trouvées lors de l'extraction du texte.<br/>            La recherche d'erreurs ne sera effectuée que si TextSearchOptions.LogTextExtractionErrors = true ; et cela peut diminuer les performances. |
| extraction_options | Obtient ou définit les options d'extraction de texte. |
| text_search_options | Obtient ou définit les options de recherche de texte. |
## Méthodes
| Nom | Description |
| :- | :- |
| visit(page) | Extrait le texte de la page spécifiée |
| visit(form) | Extrait le texte du XForm spécifié. |
| visit(pdf) | Extrait le texte du document spécifié |

### Voir aussi

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

