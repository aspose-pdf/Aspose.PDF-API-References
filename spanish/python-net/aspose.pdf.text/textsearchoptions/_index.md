---
title: "TextSearchOptions"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa opciones de búsqueda de texto"
type: docs
weight: 460
url: /es/python-net/aspose.pdf.text/textsearchoptions/
---

## TextSearchOptions class

Representa opciones de búsqueda de texto

El tipo TextSearchOptions expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| TextSearchOptions(is_regular_expression_used) | Inicializa una nueva instancia de la clase TextSearchOptions |
| TextSearchOptions(rectangle) | Inicializa una nueva instancia de la clase TextSearchOptions |
| TextSearchOptions(rectangle, is_regular_expression_used) | Inicializa una nueva instancia de la clase TextSearchOptions |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| is_regular_expression_used | Obtiene o establece la indicación de que se usa una expresión regular. |
| limit_to_page_bounds | Obtiene o establece la indicación de que el texto se busca dentro de los límites de la página. |
| rectangle | Obtiene o establece el rectángulo que delimita el texto buscado. |
| use_font_engine_encoding | Obtiene o establece la indicación de que el texto se buscará usando la codificación del motor de fuentes.<br/>            true - indica que se usará la codificación del motor de fuentes (pruebe esto si la búsqueda de texto falla debido a una codificación imperfecta en el documento)<br/>            false - indica que se usará la codificación de fuentes del documento (valor predeterminado) |
| ignore_shadow_text | Obtiene o establece la indicación de que los fragmentos de texto que representan la sombra del texto normal se ignorarán durante la búsqueda.<br/>            true - indica que el texto en sombra no se encontrará (pruebe esto si la búsqueda de texto devuelve fragmentos duplicados en posiciones cercanas)<br/>            false - indica que el texto en sombra se encontrará junto con el texto normal (valor predeterminado) |
| log_text_extraction_errors | Obtiene o establece la indicación de que los errores de extracción de texto (decodificación) se registrarán en el absorbente de texto (fragmentos).<br/>            true - indica que los errores de extracción de texto (decodificación) se registrarán. Puede disminuir el rendimiento.<br/>            false (default) - sin registro de errores. |
| ignore_resource_font_errors | Obtiene o establece la indicación de que los errores relacionados con la ausencia de fuente serán ignorados por el absorbente de fragmentos de texto.<br/>            true - significa que los errores de ausencia de fuente serán ignorados. Los segmentos de texto que hacen referencia a recursos incorrectos se omitirán durante el procesamiento.<br/>            false (default) - el error de ausencia de fuente terminará el procesamiento lanzando una excepción. |
| search_for_text_related_graphics | Obtiene o establece el valor que permite buscar gráficos relacionados con el texto (subrayado, fondo, etc.) durante la búsqueda de texto.<br/>            true - la búsqueda de gráficos relacionados con el texto se realizará (valor predeterminado).<br/>            false - los elementos gráficos que puedan estar presentes en el documento fuente serán ignorados. Configure esto en caso de problemas de rendimiento o si no es necesario manejar subrayado, fondo o recorte. |
| stored_graphic_elements_max_count | Obtiene o establece el valor que limita la búsqueda de gráficos relacionados con el texto (subrayado, fondo, etc.) en una página para el número especificado de elementos.<br/>            El valor predeterminado es 250. Establezca un valor menor en caso de problemas de rendimiento, pruebe un valor mayor si algunos elementos gráficos no se encontraron. |
| search_in_annotations | Obtiene o establece el valor que permite buscar texto en Anotaciones.<br/>            true - el texto se buscará en Anotaciones.<br/>            false - el texto en Anotaciones no será analizado por TextFragmentAbsorber. |

### Ver también

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

