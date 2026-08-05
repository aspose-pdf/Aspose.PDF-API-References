---
title: "Table"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa una tabla que puede añadirse a la página."
type: docs
weight: 1480
url: /es/python-net/aspose.pdf/table/
---

## Table class

Representa una tabla que puede añadirse a la página.

El tipo Table expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| Table() | Inicializa una nueva instancia de la clase Table |
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
| background_color | Obtiene o establece el color de fondo de la tabla |
| break_text | Obtiene o establece el texto de salto para la tabla |
| corner_style | Obtiene o establece los estilos de las esquinas del borde |
| repeating_rows_style | Obtiene el estilo para filas repetidas |
| repeating_columns_count | Obtiene o establece el número máximo de columnas para la tabla |
| repeating_rows_count | Obtiene el recuento de primeras filas repetidas en varias páginas |
| column_widths | Obtiene los anchos de columna de la tabla. |
| broken | Obtiene o establece la rotura vertical de la tabla; |
| default_cell_border | Obtiene el borde predeterminado de la celda; |
| default_column_width | Obtiene el borde predeterminado de la celda; |
| rows | Obtiene las filas de la tabla. |
| borde | Obtiene o establece el borde. |
| default_cell_padding | Obtiene o establece el relleno predeterminado de la celda. |
| default_cell_text_state | Obtiene o establece el estado de texto predeterminado de la celda. |
| alineación | Obtiene o establece la alineación de la tabla. |
| left | Obtiene o establece la coordenada izquierda de la tabla. |
| top | Obtiene o establece la coordenada superior de la tabla. |
| is_broken | Obtiene o establece si la tabla está rota - se truncará para la página siguiente. |
| is_borders_included | Obtiene o establece el borde incluido en los anchos de columna. |
| column_adjustment | Obtiene o establece el ajuste de columna de la tabla. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| clone() | Clona la tabla. |
| get_width() | Obtener ancho. |
| get_height(parent_page) | Obtener altura. |
| set_column_text_state(col_number, text_state) | Establecer altura. |
| import_array(imported_array, first_filled_row, first_filled_column, is_left_columns_filled) | Importa una matriz unidimensional de datos en la tabla. La importación coloca una celda por cada elemento de la matriz y<br/>              comienza desde la fila y columna definidas en los parámetros. Durante la importación, si se detecta que las filas necesarias<br/>              aún están ausentes (es decir, la tabla de destino es demasiado pequeña para absorber todos los datos), se crearán las filas necesarias |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

