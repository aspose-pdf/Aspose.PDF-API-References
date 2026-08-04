---
title: "ToUnicodeProcessingRules"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Cette classe décrit les règles qui peuvent être utilisées pour résoudre l'erreur Adobe Preflight <br/>            \"Le texte ne peut pas être mappé à Unicode\"."
type: docs
weight: 20
url: /fr/python-net/aspose.pdf.pdfaoptionclasses/tounicodeprocessingrules/
---

## ToUnicodeProcessingRules class

Cette classe décrit les règles qui peuvent être utilisées pour résoudre l'erreur Adobe Preflight <br/>            "Le texte ne peut pas être mappé à Unicode".

Le type ToUnicodeProcessingRules expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| ToUnicodeProcessingRules() | Constructeur |
| ToUnicodeProcessingRules(remove_spaces) | Initialise une nouvelle instance de la classe ToUnicodeProcessingRules |
| ToUnicodeProcessingRules(remove_spaces, map_non_linked_unicodes_on_space) | Initialise une nouvelle instance de la classe ToUnicodeProcessingRules |
## Propriétés
| Nom | Description |
| :- | :- |
| remove_spaces_from_c_map_names | Certaines polices ont des cartes de codes de caractères ToUnicode avec des espaces dans les noms. Ces espaces peuvent provoquer des erreurs<br/>            lors du mappage du texte Unicode. Ce drapeau indique de supprimer les espaces des noms des cartes de codes de caractères ToUnicode.<br/>            Par défaut false. |
| map_non_linked_symbols_on_space | Certaines polices ne fournissent pas d'informations sur les unicodes pour certains symboles de texte. <br/>            Cette absence d'information déclenche une erreur "Le texte ne peut pas être mappé vers Unicode".<br/>            Utilisez ce drapeau pour mapper les symboles non liés sur le "espace" Unicode (code 32). |

### Voir aussi

* namespace [aspose.pdf.pdfaoptionclasses](/pdf/python-net/aspose.pdf.pdfaoptionclasses/)
* assembly [Aspose.PDF](/pdf/python-net/)

