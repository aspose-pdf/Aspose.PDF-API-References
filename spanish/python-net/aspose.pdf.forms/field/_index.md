---
title: "Field"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase base para campos de formulario acro."
type: docs
weight: 90
url: /es/python-net/aspose.pdf.forms/field/
---

## Field class

Clase base para campos de formulario acro.

El tipo Field expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| Field(doc) | Inicializa una nueva instancia de la clase Field |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| vertical_alignment | Ninguno |
| horizontal_alignment | Obtiene o establece la alineación del texto para la anotación. |
| margen | Ninguno |
| is_first_paragraph_in_column | Ninguno |
| is_kept_with_next | Ninguno |
| is_in_new_page | Ninguno |
| is_in_line_paragraph | Ninguno |
| hipervínculo | Ninguno |
| z_index | Ninguno |
| actualizar_apariencia_al_convertir | Si es verdadero, la apariencia de la anotación se actualizará antes de convertir el documento PF en imagen. Esto permite convertir los campos correctamente pero probablemente requiera más tiempo. |
| usar_subconjunto_de_fuente | Si esta propiedad se establece en verdadero, las fuentes se agregarán al documento como subconjuntos. El valor predeterminado es verdadero. |
| banderas | Indicadores de la anotación. |
| tipo_de_anotación | Obtiene el tipo de anotación. |
| ancho | Obtiene o establece el ancho de la anotación. |
| acciones | Obtiene las acciones de la anotación. |
| alto | Obtiene o establece la altura de la anotación. |
| rectángulo | Obtiene o establece el rectángulo del campo. |
| contenidos | Obtiene o establece el texto de la anotación. |
| name | Obtiene o establece el nombre de la anotación en la página. |
| modificado | Obtiene o establece la fecha y hora en que la anotación fue modificada recientemente. |
| color | Obtiene o establece el color de la anotación. |
| border | Obtiene o establece las características del borde de la anotación. [border](/pdf/python-net/aspose.pdf.annotations/annotation/) |
| estado_activo | Obtiene o establece el estado de apariencia de la anotación actual. |
| características | Obtiene las características de la anotación. |
| estados | Obtiene el diccionario de apariencia de la anotación. |
| alineación | Alineación de anotación. Esta propiedad está obsoleta. Use HorizontalAligment en su lugar. |
| alineación_horizontal_del_texto | Obtiene o establece la alineación del texto para la anotación. |
| nombre_completo | Obtiene el nombre totalmente calificado de la anotación. |
| apariencia | Obtiene el diccionario de apariencia de la anotación. |
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
## Indexer
| Nombre | Descripción |
| :- | :- |
| [index] | Obtiene el subcampo contenido en este campo por índice. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| clone() | Ninguno |
| get_rectangle(consider_rotation) | Devuelve el rectángulo de la anotación teniendo en cuenta la rotación de la página. |
| accept(visitor) | Acepta al visitante. |
| flatten() | Elimina este campo y coloca su valor directamente en la página. |
| change_after_resize(transform) | Actualiza los parámetros y la apariencia, según la transformación de la matriz. |
| recalculate() | Recalcula todos los campos calculados en el formulario. |
| copy_to(array, index) | Copia los subcampos de este campo en la matriz comenzando desde el índice especificado. |
| set_position(point) | Establece la posición del campo. |

### Ver también

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

