---
title: "RichTextBoxField"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase que describe el componente de editor de texto enriquecido."
type: docs
weight: 240
url: /es/python-net/aspose.pdf.forms/richtextboxfield/
---

## RichTextBoxField class

Clase que describe el componente de editor de texto enriquecido.

El tipo RichTextBoxField expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| RichTextBoxField(page, rect) | Inicializa una nueva instancia de la clase RichTextBoxField |
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
| índice_de_página | Obtiene el índice de la página que contiene este campo. |
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
| value | Valor de RichTextField. |
| is_synchronized | Devuelve verdadero si el diccionario está sincronizado. |
| sync_root | Objeto de sincronización. |
| is_group | Obtiene o establece el valor booleano que indica si este campo es un campo no terminal, es decir, un grupo de campos. |
| annotation_index | Obtiene o establece el índice de esta anotación en la página. |
| is_shared_field | Propiedad para el soporte del Generador. Se usa cuando el campo se agrega al encabezado o pie de página. Si es verdadero, este campo se creará una sola vez y su apariencia será visible en todas las páginas del documento. Si es falso, se creará un campo separado para cada página del documento. |
| fit_into_rectangle | Si es verdadero, el tamaño de fuente se reducirá para ajustar el texto al rectángulo especificado. |
| max_font_size | Tamaño máximo de fuente que se puede usar para el contenido del campo. -1 para no comprobar el tamaño. |
| min_font_size | Tamaño mínimo de fuente que se puede usar para el contenido del campo. -1 para no comprobar el tamaño. |
| tab_order | Obtiene o establece el orden de tabulación del campo. |
| multiline | Obtiene o establece la bandera multiline del campo. Si Multiline es true, el campo puede contener múltiples líneas de texto. |
| spell_check | Obtiene o establece la bandera spellcheck del campo. Si true, el campo será corregido ortográficamente. |
| scrollable | Obtiene o establece la bandera scrollable del campo. Si true, el campo puede desplazarse. |
| force_combs | Obtiene o establece la bandera que indica si el campo está dividido en posiciones espaciadas. |
| max_len | Obtiene o establece la longitud máxima del texto en el campo. |
| text_vertical_alignment | Obtiene o establece la alineación vertical del texto para la anotación. |
| style | Obtiene o establece la cadena de estilo predeterminada del campo de texto enriquecido. |
| rich_text_value | Obtiene o establece el valor de texto enriquecido. |
| formatted_value | Obtiene o establece el valor de texto enriquecido formateado con marcado. |
| justify | Obtiene o establece la justificación del cuadro de texto enriquecido. |
## Indexer
| Nombre | Descripción |
| :- | :- |
| [index] | Obtiene el subcampo contenido en este campo por índice. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| clone() | Ninguno |
| get_rectangle(consider_rotation) | Ninguno |
| accept(visitor) | Ninguno |
| flatten() | Elimina este campo y coloca su valor directamente en la página. |
| change_after_resize(transform) | Ninguno |
| recalculate() | Recalcula todos los campos calculados en el formulario. |
| copy_to(array, index) | Copia los subcampos de este campo en la matriz comenzando desde el índice especificado. |
| set_position(point) | Establece la posición del campo. |
| add_image(image) | Agrega la imagen a los recursos del campo y la dibuja. |
| add_barcode(code) | Agrega el código de barras 128 al campo. <br/>            El valor del campo se cambiará al código y el campo se volverá de solo lectura. |

### Ver también

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

