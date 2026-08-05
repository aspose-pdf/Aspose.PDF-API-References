---
title: "LineAnnotation"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase que representa una anotación de línea."
type: docs
weight: 380
url: /es/python-net/aspose.pdf.annotations/lineannotation/
---

## LineAnnotation class

Clase que representa una anotación de línea.

El tipo LineAnnotation expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| LineAnnotation(document, start, end) | Inicializa una nueva instancia de la clase LineAnnotation |
| LineAnnotation(page, rect, start, end) | Inicializa una nueva instancia de la clase LineAnnotation |
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
| acciones | Obtiene la lista de acciones de anotación. |
| alto | Obtiene o establece la altura de la anotación. |
| rectángulo | Obtiene o establece el rectángulo de anotación. |
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
| índice_de_página | Obtiene el índice de la página que contiene la anotación. |
| title | Obtiene o establece un texto que se mostrará en la barra de título de la anotación. |
| rich_text | Obtiene o establece una cadena de texto enriquecido que se mostrará en la ventana emergente cuando se abra la anotación. |
| creation_date | Obtiene la fecha y hora en que se creó la anotación. |
| subject | Obtiene el texto que representa la descripción del objeto. |
| popup | Anotación emergente para ingresar o editar el texto asociado a esta anotación. |
| opacity | Obtiene o establece el valor constante de opacidad que se usará al dibujar la anotación. |
| in_reply_to | Una referencia a la anotación a la que esta anotación está "en respuesta a".<br/>            Ambas anotaciones deben estar en la misma página del documento. |
| reply_type | Una cadena que especifica la relación (el "tipo de respuesta") entre esta anotación<br/>            y la especificada por InReplyTo. |
| iniciando | Obtiene o establece el punto inicial de la línea. |
| starting_style | Obtiene o establece el estilo de terminación de línea para el punto de inicio de la línea. |
| terminación | Obtiene o establece el punto de terminación de la línea. |
| ending_style | Obtiene o establece el estilo de terminación para el punto final de la línea. |
| interior_color | Obtiene o establece el color interior de la anotación. |
| leader_line | Obtiene o establece la longitud de la línea guía. |
| leader_line_extension | Obtiene o establece la longitud de la extensión de la línea guía. |
| show_caption | Obtiene o establece la bandera booleana que determina si el contenido debe mostrarse como leyenda. |
| leader_line_offset | Obtiene o establece el desplazamiento de la línea guía. |
| caption_offset | Obtiene o establece el desplazamiento del texto de la leyenda respecto a su posición normal. |
| caption_position | Obtiene o establece la posición de la leyenda de la anotación. |
| measure | Unidades de medida especificadas para esta anotación. |
| intent | Obtiene o establece la intención de la anotación de línea. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| clone() | Ninguno |
| get_rectangle(consider_rotation) | Devuelve el rectángulo de la anotación teniendo en cuenta la rotación de la página. |
| accept(visitor) | Acepta un visitante para el procesamiento de la anotación. |
| flatten() | Coloca el contenido de la anotación directamente en la página,<br/>            el objeto de anotación será eliminado. |
| change_after_resize(transform) | Actualiza los puntos de inicio y fin, según la transformación de matriz. |

### Ver también

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

