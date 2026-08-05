---
title: "TextFragmentAbsorber"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa un objeto absorbente de fragmentos de texto.<br/>            Realiza búsquedas de texto y proporciona acceso a los resultados de búsqueda mediante la colección [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/)."
type: docs
weight: 400
url: /es/python-net/aspose.pdf.text/textfragmentabsorber/
---

## TextFragmentAbsorber class

Representa un objeto absorbente de fragmentos de texto.<br/>            Realiza búsquedas de texto y proporciona acceso a los resultados de búsqueda mediante la colección [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/).

El tipo TextFragmentAbsorber expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| TextFragmentAbsorber() | Inicializa una nueva instancia del [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) que realiza la búsqueda de todos los segmentos de texto del documento o página. |
| TextFragmentAbsorber(text_edit_options) | Inicializa una nueva instancia de la clase TextFragmentAbsorber |
| TextFragmentAbsorber(phrase) | Inicializa una nueva instancia de la clase TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_search_options) | Inicializa una nueva instancia de la clase TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_search_options, text_edit_options) | Inicializa una nueva instancia de la clase TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_edit_options) | Inicializa una nueva instancia de la clase TextFragmentAbsorber |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| text | Obtiene el texto extraído que el [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) extrae del documento PDF o página. |
| has_errors | El valor indica si se encontraron errores durante la extracción de texto.<br/>            La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; y puede disminuir el rendimiento. |
| errors | Lista de objetos [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/). Contiene información sobre los errores encontrados durante la extracción de texto.<br/>            La búsqueda de errores se realizará solo si TextSearchOptions.LogTextExtractionErrors = true; y puede disminuir el rendimiento. |
| extraction_options | Obtiene o establece las opciones de extracción de texto. |
| text_search_options | Obtiene o establece las opciones de búsqueda. Las opciones permiten buscar usando expresiones regulares. |
| text_fragments | Obtiene la colección de ocurrencias de búsqueda que se presentan con objetos [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| phrase | Obtiene o establece la frase que el [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) busca en el documento PDF o página. |
| text_edit_options | Obtiene o establece las opciones de edición de texto. Las opciones definen un comportamiento especial cuando el símbolo solicitado no puede escribirse con la fuente. |
| text_replace_options | Obtiene o establece las opciones de reemplazo de texto. Las opciones definen el comportamiento cuando el texto del fragmento se reemplaza por uno más corto o más largo. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| visit(page) | Realiza una búsqueda en la página especificada. |
| visit(pdf) | Realiza una búsqueda en el documento especificado. |
| visit(x_form) | Realiza una búsqueda en el objeto de formulario especificado. |
| apply_for_all_fragments(font) | Aplica la fuente a todos los fragmentos de texto que fueron absorbidos. Funciona más rápido que iterar sobre los fragmentos si todos los fragmentos en la(s) página(s) fueron absorbidos. De lo contrario, funciona de manera similar a la iteración. |
| apply_for_all_fragments(font_size) | Aplica el tamaño de fuente a todos los fragmentos de texto que fueron absorbidos. Funciona más rápido que iterar sobre los fragmentos si todos los fragmentos en la(s) página(s) fueron absorbidos. De lo contrario, funciona de manera similar a la iteración. |
| apply_for_all_fragments(font, font_size) | Aplica la fuente y el tamaño a todos los fragmentos de texto que fueron absorbidos. Funciona más rápido que iterar sobre los fragmentos si todos los fragmentos en la(s) página(s) fueron absorbidos. De lo contrario, funciona de manera similar a la iteración. |
| remove_all_text(page) | Elimina todo el texto de la página especificada. |
| remove_all_text(page, rect) | Elimina el texto dentro del rectángulo especificado de la página especificada. |
| remove_all_text(document) | Elimina todo el texto del documento. |
| reset() | Borra la colección TextFragments de este objeto [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/). |

### Ver también

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

