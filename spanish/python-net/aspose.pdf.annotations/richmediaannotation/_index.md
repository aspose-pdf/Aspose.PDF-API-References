---
title: "RichMediaAnnotation"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase que describe RichMediaAnnotation que permite incrustar datos de video/audio en un documento PDF."
type: docs
weight: 710
url: /es/python-net/aspose.pdf.annotations/richmediaannotation/
---

## RichMediaAnnotation class

Clase que describe RichMediaAnnotation que permite incrustar datos de video/audio en un documento PDF.

El tipo RichMediaAnnotation expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| RichMediaAnnotation(page, rect) | Inicializa una nueva instancia de la clase RichMediaAnnotation |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| vertical_alignment | Obtiene o establece una alineación vertical del párrafo |
| horizontal_alignment | Obtiene o establece la alineación del texto para la anotación. |
| margen | Obtiene o establece un margen exterior para el párrafo (para generación de pdf) |
| is_first_paragraph_in_column | Obtiene o establece un valor bool que indica si este párrafo estará en la siguiente columna.<br/>            El valor predeterminado es false. (para generación de pdf) |
| is_kept_with_next | Obtiene o establece un valor bool que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo.<br/>            El valor predeterminado es false. (para generación de pdf) |
| is_in_new_page | Obtiene o establece un valor bool que fuerza que este párrafo se genere en una nueva página.<br/>            El valor predeterminado es false. (para generación de pdf) |
| is_in_line_paragraph | Obtiene o establece si un párrafo es inline.<br/>            El valor predeterminado es false. (para generación de pdf) |
| hipervínculo | Obtiene o establece el hipervínculo del fragmento (para generador de pdf). |
| z_index | Obtiene o establece un valor entero que indica el orden Z del gráfico. Un gráfico con un ZIndex mayor <br/>            se colocará sobre el gráfico con un ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo <br/>            se colocará detrás del texto en la página. |
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
| custom_player | Establece o obtiene el reproductor flash personalizado para reproducir datos de video/audio. |
| custom_flash_variables | Establece o obtiene variables flash que se pasan al reproductor. |
| content | Datos del contenido Rich Media. |
| type | Obtiene o establece el tipo de contenido. Valores posibles: Audio, Video. |
| activate_on | Evento que activa la aplicación. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| clone() | Clona esta instancia.<br/>            Método virtual. Siempre devuelve null. |
| get_rectangle(consider_rotation) | Devuelve el rectángulo de la anotación teniendo en cuenta la rotación de la página. |
| accept(visitor) | Acepta visitante para esta anotación. |
| flatten() | Coloca el contenido de la anotación directamente en la página,<br/>            el objeto de anotación será eliminado. |
| change_after_resize(transform) | Actualiza los parámetros y la apariencia, según la transformación de la matriz. |
| add_custom_data(name, data) | Agrega datos personalizados con nombre (por ejemplo, requerido para el script flash). |
| set_content(file_name, audio) | Establece el flujo de contenido. |
| set_poster(image_stream) | Establece el póster de la anotación. |
| update() | Actualiza los datos con los parámetros especificados. |

### Ver también

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

