---
title: "TextSearchOptions"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente les options de recherche de texte"
type: docs
weight: 460
url: /fr/python-net/aspose.pdf.text/textsearchoptions/
---

## TextSearchOptions class

Représente les options de recherche de texte

Le type TextSearchOptions expose les membres suivants:
## Constructeurs
| Nom | Description |
| :- | :- |
| TextSearchOptions(is_regular_expression_used) | Initialise une nouvelle instance de la classe TextSearchOptions |
| TextSearchOptions(rectangle) | Initialise une nouvelle instance de la classe TextSearchOptions |
| TextSearchOptions(rectangle, is_regular_expression_used) | Initialise une nouvelle instance de la classe TextSearchOptions |
## Propriétés
| Nom | Description |
| :- | :- |
| is_regular_expression_used | Obtient ou définit l'indication qu'une expression régulière est utilisée. |
| limit_to_page_bounds | Obtient ou définit l'indication que le texte est recherché dans les limites de la page. |
| rectangle | Obtient ou définit le rectangle qui délimite le texte recherché. |
| use_font_engine_encoding | Obtient ou définit l'indication que le texte sera recherché en utilisant le codage du moteur de police.<br/>            true - indique que le codage du moteur de police sera utilisé (essayez cela si la recherche de texte échoue à cause d'un codage imparfait dans le document)<br/>            false - indique que le codage de police du document sera utilisé (valeur par défaut) |
| ignore_shadow_text | Obtient ou définit l'indication que les fragments de texte représentant l'ombre du texte normal seront ignorés lors de la recherche.<br/>            true - indique que le texte d'ombre ne sera pas trouvé (essayez cela si la recherche de texte renvoie des fragments dupliqués à des positions proches)<br/>            false - indique que le texte d'ombre sera trouvé ainsi que le texte normal (valeur par défaut) |
| log_text_extraction_errors | Obtient ou définit l'indication que les erreurs d'extraction de texte (décodage) seront enregistrées dans l'absorbeur de texte (fragment).<br/>            true - indique que les erreurs d'extraction de texte (décodage) seront enregistrées. Cela peut diminuer les performances.<br/>            false (par défaut) - aucune journalisation des erreurs. |
| ignore_resource_font_errors | Obtient ou définit l'indication selon laquelle les erreurs liées à l'absence de police seront ignorées par l'absorbeur de texte (fragment).<br/>            true - signifie que les erreurs d'absence de police seront ignorées. Les segments de texte qui font référence à des ressources incorrectes seront sautés pendant le traitement.<br/>            false (par défaut) - l'erreur d'absence de police terminera le traitement en lançant une exception. |
| search_for_text_related_graphics | Obtient ou définit la valeur qui autorise la recherche de graphiques liés au texte (soulignement, arrière-plan, etc.) lors de la recherche de texte.<br/>            true - la recherche de graphiques liés au texte sera effectuée (valeur par défaut).<br/>            false - les éléments graphiques pouvant être présents dans le document source seront ignorés. Activez ceci en cas de problèmes de performance ou si vous n'avez pas besoin de gérer le soulignement, l'arrière-plan ou le découpage. |
| stored_graphic_elements_max_count | Obtient ou définit la valeur qui limite la recherche de graphiques liés au texte (soulignement, arrière-plan, etc.) sur une page au nombre spécifié d'éléments.<br/>            La valeur par défaut est 250. Réduisez la valeur en cas de problèmes de performance, essayez une valeur plus grande si certains éléments graphiques n'ont pas été trouvés. |
| search_in_annotations | Obtient ou définit la valeur qui autorise la recherche de texte dans les annotations.<br/>            true - le texte sera recherché dans les annotations.<br/>            false - le texte dans les annotations ne sera pas analysé par TextFragmentAbsorber. |

### Voir aussi

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

