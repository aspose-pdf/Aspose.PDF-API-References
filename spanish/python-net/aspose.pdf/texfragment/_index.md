---
title: "TeXFragment"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa un fragmento TeX."
type: docs
weight: 1510
url: /es/python-net/aspose.pdf/texfragment/
---

## TeXFragment class

Representa un fragmento TeX.

El tipo TeXFragment expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| TeXFragment(text) | Inicializa una nueva instancia de la clase TeXFragment |
| TeXFragment(text, remove_indents) | Inicializa una nueva instancia de la clase TeXFragment |
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
| te_x_load_options_of_instance | Obtiene o establece TeXLoadOptions que se utilizarán para cargar (y renderizar) LaTeX en esta instancia de la clase.<br/>            Úselo cuando sea necesario aplicar una configuración específica para la importación de LaTeX en esta u otra instancia<br/>             (p. ej. cuando esta u otra instancia debe usar una BasePath específica para LaTeX importado o debe usar un cargador específico de recursos externos)<br/>            Si el parámetro es el valor predeterminado (null), se utilizarán las opciones estándar de carga de LaTeX. |
| latex_load_options_of_instance | Obtiene o establece TeXLoadOptions que se utilizarán para cargar (y renderizar) LaTeX en esta instancia de la clase.<br/>            Úselo cuando sea necesario aplicar una configuración específica para la importación de LaTeX en esta u otra instancia<br/>             (p. ej. cuando esta u otra instancia debe usar una BasePath específica para LaTeX importado o debe usar un cargador específico de recursos externos)<br/>            Si el parámetro es el valor predeterminado (null), se utilizarán las opciones estándar de carga de LaTeX. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| clone() | Clona el fragmento. |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

