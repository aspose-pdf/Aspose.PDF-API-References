---
title: "MovieAnnotation"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa una anotación de película que contiene gráficos animados y sonido para presentarse en la pantalla del ordenador y a través de los altavoces. Cuando la anotación se activa, la película se reproduce."
type: docs
weight: 480
url: /es/python-net/aspose.pdf.annotations/movieannotation/
---

## MovieAnnotation class

Representa una anotación de película que contiene gráficos animados y sonido para presentarse en la pantalla del ordenador y a través de los altavoces. Cuando la anotación se activa, la película se reproduce.

El tipo MovieAnnotation expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| MovieAnnotation(document, movie_file) | Inicializa una nueva instancia de la clase MovieAnnotation |
| MovieAnnotation(page, rect, movie_file) | Inicializa una nueva instancia de la clase MovieAnnotation |
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
| title | Obtiene o establece el título de la anotación de película. |
| file | Obtiene o establece una especificación de archivo que identifica un archivo de película auto‑descriptivo. |
| poster | Obtiene o establece una bandera o flujo que especifica si y cómo se mostrará una imagen de póster que representa la película. Si es true, la imagen del póster se obtendrá del archivo de película; si es false, no se mostrará ningún póster. |
| aspect | Obtiene o establece el ancho y la altura del cuadro delimitador de la película, en píxeles. |
| rotar | Obtiene o establece el número de grados en que la película se rotará en sentido horario respecto a la página. El valor debe ser un múltiplo de 90. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| clone() | Clona esta instancia.<br/>            Método virtual. Siempre devuelve null. |
| get_rectangle(consider_rotation) | Devuelve el rectángulo de la anotación teniendo en cuenta la rotación de la página. |
| accept(visitor) | Acepta un objeto visitante para procesar la anotación. |
| flatten() | Coloca el contenido de la anotación directamente en la página,<br/>            el objeto de anotación será eliminado. |
| change_after_resize(transform) | Actualiza los parámetros y la apariencia, según la transformación de la matriz. |

### Ver también

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

