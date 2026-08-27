---
title: "FreeTextAnnotation"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa una anotación de texto libre que muestra texto directamente en la página. A diferencia de una anotación de texto ordinaria, una anotación de texto libre no tiene estado abierto o cerrado; en lugar de mostrarse en una ventana emergente, el texto siempre es visible."
type: docs
weight: 260
url: /es/python-net/aspose.pdf.annotations/freetextannotation/
---

## FreeTextAnnotation class

Representa una anotación de texto libre que muestra texto directamente en la página. A diferencia de una anotación de texto ordinaria, una anotación de texto libre no tiene estado abierto o cerrado; en lugar de mostrarse en una ventana emergente, el texto siempre es visible.

El tipo FreeTextAnnotation expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| FreeTextAnnotation(document, appearance) | Inicializa una nueva instancia de la clase FreeTextAnnotation |
| FreeTextAnnotation(page, rect, appearance) | Inicializa una nueva instancia de la clase FreeTextAnnotation |
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
| starting_style | Obtiene o establece el estilo de terminación de línea para el punto final de la línea.<br/>            OEsta propiedad está obsoleta, por favor use EndingStyle. |
| ending_style | Obtiene o establece el estilo de terminación de línea para el punto final de la línea. |
| justification | Obtiene o establece un código que especifica la forma de justificación (justification) que se usará al mostrar el texto de la anotación. |
| default_appearance | Obtiene o establece la cadena de apariencia predeterminada que se usará al formatear el texto. |
| default_appearance_object | Objeto que representa la apariencia predeterminada de la anotación FreeText. |
| intent | Obtiene o establece la intención de la anotación de texto libre. |
| default_style | Obtiene o establece una cadena de estilo predeterminada. |
| text_style | Obtiene o establece el estilo del texto en la apariencia. Cuando se cambia el estilo del texto, la apariencia del texto se actualiza. |
| rotar | Ángulo de rotación de la anotación. |
| llamada | Matriz de puntos que especifican la línea de llamada. |
| text_rectangle | Rectángulo que describe las diferencias numéricas entre dos rectángulos: la entrada Rect de la anotación<br/>             y un rectángulo contenido dentro de ese rectángulo. El rectángulo interno es donde se debe mostrar el texto de la anotación. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| clone() | Ninguno |
| get_rectangle(consider_rotation) | Devuelve el rectángulo de la anotación teniendo en cuenta la rotación de la página. |
| accept(visitor) | Acepta un objeto visitante para procesar la anotación. |
| flatten() | Coloca el contenido de la anotación directamente en la página,<br/>            el objeto de anotación será eliminado. |
| change_after_resize(transform) | Actualiza los parámetros y la apariencia, según la transformación de la matriz. |

### Ver también

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

