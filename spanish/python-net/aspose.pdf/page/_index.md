---
title: "Page"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase que representa una página de un documento PDF."
type: docs
weight: 1080
url: /es/python-net/aspose.pdf/page/
---

## Page class

Clase que representa una página de un documento PDF.

El tipo Page expone los siguientes miembros:
## Propiedades
| Nombre | Descripción |
| :- | :- |
| is_add_paragraphs_after_last | Obtiene o establece la adición de párrafos después del último párrafo de la página |
| background_image | Obtiene o establece la imagen de fondo para la página (solo para el generador, no se rellena al leer el documento). |
| toc_info | Obtiene o establece la información del índice. |
| header | Obtiene o establece el encabezado de la página. |
| capas | Obtiene o establece la colección de capas. |
| pie de página | Obtiene o establece el pie de página. |
| paragraphs | Obtiene los párrafos. |
| page_info | Obtiene o establece la información de la página (solo para el generador, no se completa al leer el documento). |
| rectángulo | Obtiene o establece el rectángulo de la página.<br/>            Para obtener: se devuelve el recorte de la página si está especificado, de lo contrario se devuelve el cuadro de medios de la página.<br/>            Para establecer: siempre se establece el cuadro de medios de la página.<br/>            Tenga en cuenta que esta propiedad no considera la rotación de la página. Para obtener el rectángulo de la página considerando la rotación, use ActualRect. |
| color_type | Establece el tipo de color de las páginas basado en la información obtenida de los operadores SetColor,<br/>            imágenes y formularios. |
| note_line_style | Obtiene o establece el estilo de línea para notas (solo para el generador, no se completa al leer el documento). |
| tab_order | Obtiene o establece el orden de tabulación de la página. <br/>            Valores posibles: Row, Column. Predeterminado, Manual |
| duration | Obtiene o establece la duración de visualización de la página. Este es el tiempo en segundos que la página se mostrará durante la presentación.<br/>            Devuelve -1 si la duración no está definida. |
| contents | Obtiene la colección de operadores en el flujo de contenido de la página.<br/>            [OperatorCollection](/pdf/python-net/aspose.pdf/operatorcollection/) |
| grupo | Obtiene o establece una clase de atributos de grupo que especifica los atributos del grupo de página de la página para su uso en el modelo de imágenes transparentes. |
| annotations | Obtiene la colección de anotaciones de la página.<br/>            [annotations](/pdf/python-net/aspose.pdf/page/) |
| resources | Obtiene los recursos de la página. El objeto Resources contiene colecciones de imágenes, formularios y fuentes.<br/>            [resources](/pdf/python-net/aspose.pdf/page/) |
| rotar | Obtiene o establece la rotación de la página. |
| trim_box | Obtiene o establece el trim box de la página. |
| art_box | Obtiene o establece el art box de la página. |
| bleed_box | Obtiene o establece el cuadro de sangrado de la página. |
| crop_box | Obtiene o establece el cuadro de recorte de la página. |
| media_box | Obtiene o establece el cuadro de medios de la página. |
| número | Obtiene el número de la página. |
| rotation_matrix | Obtiene la matriz de transformación de la página. |
| background | Obtiene o establece el color de fondo de la página. |
| watermark | Obtiene o establece la marca de agua de la página. |
| artifacts | Obtiene la colección de artefactos en la página. |
| acciones | Obtiene la colección de propiedades de la página. |
| fields_in_tab_order | Obtiene la lista de objetos Field en orden de tabulación en esta página. |
| user_unit | Obtiene o establece el valor UserUnit. Un número positivo que indica el tamaño de las unidades de espacio de usuario predeterminadas, en múltiplos de 1 ⁄ 72 pulgada.<br/>            El valor predeterminado es 1. Por favor, establezca cero o un valor negativo para borrar esta entrada en la página. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| send_to(device, output) | Envía la página para procesar con el dispositivo de página proporcionado. |
| send_to(device, output_file_name) | Envía la página para procesar con el dispositivo de página proporcionado. |
| accept(visitor) | Acepta el objeto visitante [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/) que proporciona funcionalidad para trabajar con anotaciones. |
| accept(visitor) | Acepta el objeto visitante [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) que proporciona funcionalidad para trabajar con objetos de texto. |
| accept(visitor) | Acepta el objeto visitante [ImagePlacementAbsorber](/pdf/python-net/aspose.pdf/imageplacementabsorber/) que proporciona funcionalidad para trabajar con objetos de colocación de imágenes. |
| accept(visitor) | Acepta el objeto visitante [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) que proporciona funcionalidad para trabajar con objetos de texto. |
| add_image(image_stream, image_rect) | Añade una imagen a la página y la coloca en el centro del rectángulo especificado preservando la proporción de la imagen. |
| add_image(hocr, image_stream, image_rect) | Añade una imagen buscable a la página y la coloca en el centro del rectángulo especificado preservando la proporción de la imagen. |
| add_image(image_stream, image_rect, image_width, image_height, save_image_proportions) | Agrega una imagen en la página y la coloca según la posición del rectángulo de la imagen. |
| add_image(image_path, rectangle) | Añade una imagen buscable a la página y la coloca en el centro del rectángulo especificado preservando la proporción de la imagen. |
| is_blank(fill_threshold_factor) | Obtiene la bandera que indica si la página está en blanco o no. |
| get_page_rect(consider_rotation) | Devuelve el rectángulo de la página según su CropBox (o MediaBox si CropBox es nulo). |
| calculate_content_b_box() | Calcula el valor del bbox: rectángulo que contiene el contenido sin márgenes visibles. |
| rotation_to_int(rotation) | Traduce el miembro de enumeración de rotación a un valor entero. |
| int_to_rotation(rotation) | Traduce el valor entero al miembro correspondiente de la enumeración de rotación. |
| add_stamp(stamp) | Coloca un sello en la página. El sello puede ser el número de página, una imagen o texto simple, p. ej., algún logotipo. |
| flatten() | Elimina todos los campos ubicados en la página y coloca sus valores en su lugar. |
| set_page_size(width, height) | Establece el tamaño de la página. |
| make_grayscale() | Convierte la página a escala de grises. |
| free_memory() | Borra los datos en caché |
| get_notifications() | Devuelve notificaciones sobre operaciones internas con el contenido de la página. (Solo se admiten notificaciones sobre eventos de párrafo en escenarios de adición de texto.) |
| as_byte_array(resolution) | Convierte la página actual a bitmap y luego devuelve una matriz de bytes. |
| as_xml() | Convierte la página actual a XML con codificación UTF-8. |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

