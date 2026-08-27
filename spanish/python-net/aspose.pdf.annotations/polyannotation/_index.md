---
title: "PolyAnnotation"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase base abstracta para polianotaciones."
type: docs
weight: 640
url: /es/python-net/aspose.pdf.annotations/polyannotation/
---

## PolyAnnotation class

Clase base abstracta para polianotaciones.

El tipo PolyAnnotation expone los siguientes miembros:
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
| measure | Unidades de medida especificadas para esta anotación. |
| vertices | Obtiene o establece una matriz de puntos que representan las coordenadas horizontales y verticales de cada vértice. |
| interior_color | Obtiene o establece el color interior con el que rellenar los extremos de línea de la anotación. |
| starting_style | Obtiene o establece el estilo del primer extremo de línea. |
| ending_style | Obtiene o establece el estilo del segundo extremo de línea. |
| intent | Obtiene o establece la intención de la anotación de polígono o polilínea. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| clone() | Ninguno |
| get_rectangle(consider_rotation) | Devuelve el rectángulo de la anotación teniendo en cuenta la rotación de la página. |
| accept(visitor) | Acepta un visitante para el procesamiento de anotaciones. |
| flatten() | Coloca el contenido de la anotación directamente en la página,<br/>            el objeto de anotación será eliminado. |
| change_after_resize(transform) | Actualiza los puntos en Vertices, según la transformación matricial. |

### Ver también

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

