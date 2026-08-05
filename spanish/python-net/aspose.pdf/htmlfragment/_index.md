---
title: "HtmlFragment"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa un fragmento html."
type: docs
weight: 470
url: /es/python-net/aspose.pdf/htmlfragment/
---

## HtmlFragment class

Representa un fragmento html.

El tipo HtmlFragment expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| HtmlFragment(text) | Inicializa una nueva instancia de la clase HtmlFragment |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| vertical_alignment | Obtiene o establece una alineación vertical del párrafo |
| horizontal_alignment | Obtiene o establece una alineación horizontal del párrafo |
| margen | Obtiene o establece un margen exterior para el párrafo (para generación de pdf) |
| is_first_paragraph_in_column | Obtiene o establece un valor bool que indica si este párrafo estará en la siguiente columna.<br/>            El valor predeterminado es false. (para generación de pdf) |
| is_kept_with_next | Obtiene o establece un valor bool que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo.<br/>            El valor predeterminado es false. (para generación de pdf) |
| is_in_new_page | Obtiene o establece un valor bool que fuerza que este párrafo se genere en una nueva página.<br/>            El valor predeterminado es false. (para generación de pdf) |
| is_in_line_paragraph | Obtiene o establece si un párrafo es inline.<br/>            El valor predeterminado es false. (para generación de pdf) |
| hipervínculo | Obtiene o establece el hipervínculo del fragmento (para generador de pdf). |
| z_index | Obtiene o establece un valor entero que indica el orden Z del gráfico. Un gráfico con un ZIndex mayor <br/>            se colocará sobre el gráfico con un ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo <br/>            se colocará detrás del texto en la página. |
| rectangle | Obtiene el rectángulo del HtmlFragment |
| is_paragraph_has_margin | Obtiene o establece si el párrafo tiene margen predeterminado; de lo contrario, el margen es 0 |
| is_break_words | Obtiene o establece la ruptura de palabras |
| text_state | Obtiene o establece la fuente |
| html_load_options | Obtiene o establece HtmlLoadOptions que se utilizarán para cargar (y renderizar) HTML en esta instancia de la clase.<br/>            Por favor, úselo cuando sea necesario usar una configuración específica para la importación de HTML para esta u otra instancia<br/>             (p. ej., cuando esta u otra instancia deba usar una BasePath específica para el HTML importado o deba usar un cargador específico de recursos externos)<br/>            Si el parámetro es predeterminado (null), se utilizarán las opciones estándar de carga de HTML. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| clone() | Clona el fragmento HTML. |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

