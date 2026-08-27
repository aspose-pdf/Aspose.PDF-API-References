---
title: "ButtonField"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase que representa un campo de botón pulsador."
type: docs
weight: 20
url: /es/python-net/aspose.pdf.forms/buttonfield/
---

## ButtonField class

Clase que representa un campo de botón pulsador.

El tipo ButtonField expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| ButtonField() | Constructor de campo Button para Generator. |
| ButtonField(page, rect) | Inicializa una nueva instancia de la clase ButtonField |
| ButtonField(doc, rect) | Inicializa una nueva instancia de la clase ButtonField |
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
| tipo_de_anotación | Obtiene el tipo de anotación. |
| ancho | Ninguno |
| acciones | Obtiene las acciones de la anotación. |
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
| índice_de_página | Obtiene el índice de la página que contiene este campo. |
| al_activarse | Una acción que se realizará cuando la anotación se active. |
| resaltado | Modo de resaltado de anotación. |
| padre | Obtiene el padre de la anotación. |
| default_appearance | Obtiene o establece la apariencia predeterminada del campo. |
| read_only | Obtiene o establece el estado de solo lectura del campo. |
| required | Obtiene o establece el estado requerido del campo. |
| exportable | Obtiene o establece la bandera exportable del campo. |
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
| normal_caption | Obtiene o establece la leyenda normal. |
| rollover_caption | Obtiene o establece la leyenda al pasar el cursor del botón que se mostrará cuando el usuario desplace el cursor <br/>            a su área activa sin presionar el botón del ratón. |
| alternate_caption | Obtiene o establece la leyenda alternativa del botón que se mostrará <br/>            cuando se presione el botón del ratón dentro de su área activa. |
| normal_icon | Obtiene o establece el ícono normal del botón que se mostrará cuando no esté interactuando con el usuario. |
| rollover_icon | Obtiene o establece el ícono al pasar el cursor del botón que se mostrará cuando el usuario <br/>            desplace el cursor a su área activa sin presionar el botón del ratón. |
| alternate_icon | Obtiene o establece el ícono alternativo que se mostrará cuando se presione el botón del ratón dentro de su área activa. |
| icon_fit | Obtiene el objeto de ajuste de ícono que especifica cómo se mostrará el ícono de la anotación del widget dentro de su rectángulo de anotación. |
| ic_position | Obtiene o establece la posición de la leyenda del ícono. |
## Indexer
| Nombre | Descripción |
| :- | :- |
| [index] | Obtiene el subcampo contenido en este campo por índice. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| clone() | Ninguno |
| get_rectangle(consider_rotation) | Ninguno |
| accept(visitor) | Acepta al visitante. |
| flatten() | Elimina este campo y coloca su valor directamente en la página. |
| change_after_resize(transform) | Ninguno |
| recalculate() | Recalcula todos los campos calculados en el formulario. |
| copy_to(array, index) | Copia los subcampos de este campo en la matriz comenzando desde el índice especificado. |
| set_position(point) | Establece la posición del campo. |
| add_image(image) | Agrega la imagen a los recursos del campo y la dibuja. |

### Ver también

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

