---
title: "RadioButtonField"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase que representa el campo de botón de opción."
type: docs
weight: 220
url: /es/python-net/aspose.pdf.forms/radiobuttonfield/
---

## RadioButtonField class

Clase que representa el campo de botón de opción.

El tipo RadioButtonField expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| RadioButtonField(page) | Inicializa una nueva instancia de la clase RadioButtonField |
| RadioButtonField(doc) | Inicializa una nueva instancia de la clase RadioButtonField |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| vertical_alignment | Ninguno |
| horizontal_alignment | Ninguno |
| margen | Ninguno |
| is_first_paragraph_in_column | Ninguno |
| is_kept_with_next | Ninguno |
| is_in_new_page | Ninguno |
| is_in_line_paragraph | Ninguno |
| hipervínculo | Ninguno |
| z_index | Ninguno |
| actualizar_apariencia_al_convertir | Ninguno |
| usar_subconjunto_de_fuente | Ninguno |
| banderas | Ninguno |
| tipo_de_anotación | Ninguno |
| ancho | Ninguno |
| acciones | Ninguno |
| alto | Ninguno |
| rectángulo | Obtiene o establece el rectángulo del campo. |
| contenidos | Ninguno |
| name | Ninguno |
| modificado | Ninguno |
| color | Ninguno |
| borde | Ninguno |
| estado_activo | Ninguno |
| características | Ninguno |
| estados | Ninguno |
| alineación | Ninguno |
| alineación_horizontal_del_texto | Ninguno |
| nombre_completo | Ninguno |
| apariencia | Ninguno |
| índice_de_página | Obtiene el índice de la página que contiene este campo RadioButton. |
| al_activarse | Ninguno |
| resaltado | Ninguno |
| padre | Ninguno |
| default_appearance | Ninguno |
| read_only | Ninguno |
| required | Ninguno |
| exportable | Ninguno |
| partial_name | Obtiene o establece el nombre parcial del campo. |
| alternate_name | Obtiene o establece el nombre alternativo del campo (Un campo alternativo <br/>            nombre que se debe usar en lugar del nombre real del campo <br/>            dondequiera que el campo deba identificarse en la interfaz de usuario).<br/>            El nombre alternativo se usa como información sobre herramientas del campo en Adobe Acrobat. |
| mapping_name | Obtiene o establece el nombre de mapeo del campo que se debe usar al exportar los datos de campos de formulario interactivo del documento. |
| value | Obtiene o establece el valor del campo. |
| is_synchronized | Devuelve verdadero si el diccionario está sincronizado. |
| sync_root | Objeto de sincronización. |
| is_group | Obtiene o establece el valor booleano que indica si este campo es un campo no terminal, es decir, un grupo de campos. |
| annotation_index | Obtiene o establece el índice de esta anotación en la página. |
| is_shared_field | Propiedad para el soporte del Generador. Se usa cuando el campo se agrega al encabezado o pie de página. Si es verdadero, este campo se creará una sola vez y su apariencia será visible en todas las páginas del documento. Si es falso, se creará un campo separado para cada página del documento. |
| fit_into_rectangle | Si es verdadero, el tamaño de fuente se reducirá para ajustar el texto al rectángulo especificado. |
| max_font_size | Tamaño máximo de fuente que se puede usar para el contenido del campo. -1 para no comprobar el tamaño. |
| min_font_size | Tamaño mínimo de fuente que se puede usar para el contenido del campo. -1 para no comprobar el tamaño. |
| tab_order | Obtiene o establece el orden de tabulación del campo. |
| commit_immediately | Obtiene o establece la bandera de confirmación al cambiar la selección. |
| multi_select | Obtiene o establece la bandera de selección múltiple. |
| selected | Obtiene o establece el índice del elemento seleccionado. La numeración de los elementos comienza en 1. |
| selected_items | Obtiene o establece la matriz de elementos seleccionados. Para una lista de selección múltiple, la matriz contiene más de un elemento. Para una lista de selección única, contiene un solo elemento. |
| opciones | Obtiene la colección de opciones del botón de opción. |
| style | Estilo del cuadro del campo. |
## Indexer
| Nombre | Descripción |
| :- | :- |
| [index] | Obtiene el subcampo contenido en este campo por índice. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| add_option(option_name, rect) | Agregar a la opción del botón de radio con rectángulo especificado. |
| add_option(option_name) | Agregar a la opción del botón de radio con rectángulo especificado. |
| add_option(export, name) | Agregar a la opción del botón de radio con rectángulo especificado. |
| clone() | Ninguno |
| get_rectangle(consider_rotation) | Ninguno |
| accept(visitor) | Ninguno |
| flatten() | Elimina este campo y coloca su valor directamente en la página. |
| change_after_resize(transform) | Ninguno |
| recalculate() | Recalcula todos los campos calculados en el formulario. |
| copy_to(array, index) | Copia los subcampos de este campo en la matriz comenzando desde el índice especificado. |
| set_position(point) | Mover todos los subelementos del botón de radio a las posiciones especificadas en la página. |
| delete_option(option_name) | Elimina la opción por su nombre. |
| add(new_item) | Agrega un nuevo campo de opción al campo RadioButton |

### Ver también

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

