---
title: "WatermarkArtifact"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "La clase describe el artefacto de marca de agua. Esto puede usarse para"
type: docs
weight: 1640
url: /es/python-net/aspose.pdf/watermarkartifact/
---

## WatermarkArtifact class

La clase describe el artefacto de marca de agua. Esto puede usarse para

El tipo WatermarkArtifact expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| WatermarkArtifact() | Crea una instancia del artefacto Watermark. |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| custom_type | Obtiene el nombre del tipo de artifact. Puede usarse si el tipo de artifact no es estándar. |
| custom_subtype | Obtiene el nombre del subtipo de artifact. Puede usarse si el subtipo de artifact no es un subtipo estándar. |
| type | Obtiene el tipo de artifact. |
| subtype | Obtiene el subtipo de artifact. Si artifact tiene un subtipo no estándar, el nombre del subtipo puede leerse a través de CustomSubtype. |
| contenidos | Obtiene la colección de operadores internos de artifact. |
| formulario | Obtiene XForm del artifact (si se usa XForm). |
| rectangle | Obtiene el rectángulo del artifact. |
| position | Obtiene o establece la posición del artifact.<br/>            Si se especifica esta propiedad, los márgenes y alineaciones se ignoran. |
| right_margin | Margen derecho del artifact. <br/>            Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| left_margin | Margen izquierdo del artifact. <br/>            Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| top_margin | Margen superior del artifact. <br/>            Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| bottom_margin | Margen inferior del artifact. <br/>            Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| artifact_horizontal_alignment | Alineación horizontal del artifact. <br/>            Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| artifact_vertical_alignment | Alineación vertical del artefacto. <br/>            Si la posición se especifica explícitamente (en la propiedad Position) este valor se ignora. |
| rotation | Obtiene o establece el ángulo de rotación del artefacto. |
| text | Obtiene el texto del artefacto. |
| image | Obtiene la imagen del artefacto (si está presente). |
| opacity | Obtiene o establece la opacidad del artefacto. Los valores posibles están en el rango 0..1. |
| líneas | Líneas del artefacto de texto multilínea. |
| text_state | Estado de texto para el texto del artefacto. |
| is_background | Si es verdadero, el artefacto se coloca detrás del contenido de la página. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| set_image(image_stream) | Establece la imagen del artefacto. |
| set_image(image_name) | Establece la imagen del artefacto. |
| set_text(formatted_text) | Establece el texto del artefacto. |
| set_text_and_state(text, text_state) | Establece el texto y las propiedades del texto del artefacto. |
| set_lines_and_state(text, text_state) | Establece el texto y las propiedades del texto del artefacto. Permite especificar múltiples líneas. |
| set_pdf_page(page) | Establece la página PDF que se coloca en la página del documento como artefacto. |
| get_value(name) | Obtiene el valor personalizado del artefacto. |
| set_value(name, value) | Establece el valor personalizado del artefacto. |
| remove_value(name) | Elimina el valor personalizado del artefacto. |
| begin_updates() | Inicie actualizaciones retrasadas. Use esta función si necesita realizar varios cambios en el mismo artefacto para mejorar el rendimiento. <br/>            Normalmente los operadores del artefacto se cambian cada vez que se modifica una propiedad del artefacto. Esto provoca el cambio del contenido de la página<br/>            cada vez que el artefacto se modifica. Para evitar este efecto, coloque todas las actualizaciones del artefacto entre las llamadas StartUpdates/SaveUpdates.<br/>            Esto permite cambiar el contenido de la página solo una vez. |
| save_updates() | Guarda todas las actualizaciones en el artefacto que se realizaron después de la llamada a BeginUpdates(). |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

