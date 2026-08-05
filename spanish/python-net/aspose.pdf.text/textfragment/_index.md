---
title: "TextFragment"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa un fragmento de texto Pdf."
type: docs
weight: 390
url: /es/python-net/aspose.pdf.text/textfragment/
---

## TextFragment class

Representa un fragmento de texto Pdf.

El tipo TextFragment expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| TextFragment() | Inicializa una nueva instancia del objeto [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| TextFragment(tab_stops) | Inicializa una nueva instancia de la clase TextFragment |
| TextFragment(text) | Inicializa una nueva instancia de la clase TextFragment |
| TextFragment(text, tab_stops) | Inicializa una nueva instancia de la clase TextFragment |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| vertical_alignment | Obtiene o establece una alineación vertical del fragmento de texto. |
| horizontal_alignment | Obtiene o establece una alineación horizontal del fragmento de texto. |
| margen | Obtiene o establece un margen exterior para el párrafo (para generación de pdf) |
| is_first_paragraph_in_column | Obtiene o establece un valor bool que indica si este párrafo estará en la siguiente columna.<br/>            El valor predeterminado es false. (para generación de pdf) |
| is_kept_with_next | Obtiene o establece un valor bool que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo.<br/>            El valor predeterminado es false. (para generación de pdf) |
| is_in_new_page | Obtiene o establece un valor bool que fuerza que este párrafo se genere en una nueva página.<br/>            El valor predeterminado es false. (para generación de pdf) |
| is_in_line_paragraph | Obtiene o establece si un párrafo es inline.<br/>            El valor predeterminado es false. (para generación de pdf) |
| hipervínculo | Establece el hipervínculo del fragmento |
| z_index | Obtiene o establece un valor entero que indica el orden Z del gráfico. Un gráfico con un ZIndex mayor <br/>            se colocará sobre el gráfico con un ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo <br/>            se colocará detrás del texto en la página. |
| replace_options | Obtiene las opciones de reemplazo de texto. Las opciones definen el comportamiento cuando el texto del fragmento se reemplaza por uno más corto o más largo. |
| text | Obtiene o establece el objeto de texto cadena que representa el objeto [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| text_state | Obtiene o establece el estado del texto para el texto que representa el objeto [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| segments | Obtiene los segmentos de texto para el [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) actual. |
| position | Obtiene o establece la posición del texto, representado con el objeto [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| baseline_position | Obtiene la posición del texto, representado con el objeto [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/).<br/>            El YIndent de la estructura Position representa la coordenada de la línea base del fragmento de texto. |
| rectangle | Obtiene el rectángulo del TextFragment |
| página | Obtiene la página que contiene el TextFragment |
| formulario | Obtiene el objeto de formulario que contiene el TextFragment |
| wrap_lines_count | Obtiene o establece el recuento de líneas de ajuste para este párrafo (solo para generación de PDF) |
| end_note | Obtiene o establece la nota final del párrafo (solo para generación de PDF). |
| foot_note | Obtiene o establece la nota al pie del párrafo (solo para generación de PDF). |
## Métodos
| Nombre | Descripción |
| :- | :- |
| clone() | Clonar el fragmento. |
| isolate_text_segments(start_index, length) | Obtiene [TextSegment](/pdf/python-net/aspose.pdf.text/textsegment/)(s) que representan la parte especificada del texto del [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| clone_with_segments() | Clonar el fragmento con todos los segmentos. |

### Ver también

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

