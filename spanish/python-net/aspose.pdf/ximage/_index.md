---
title: "XImage"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase que representa el X-Object de imagen."
type: docs
weight: 1680
url: /es/python-net/aspose.pdf/ximage/
---

## XImage class

Clase que representa el X-Object de imagen.

El tipo XImage expone los siguientes miembros:
## Propiedades
| Nombre | Descripción |
| :- | :- |
| contains_transparency | Si la imagen contiene transparencia, devuelve true; de lo contrario, false. |
| grayscaled | Obtiene la versión en escala de grises de la imagen. |
| filter_type | Obtiene el tipo de filtro de imagen. |
| ancho | Obtiene el ancho de la imagen. |
| alto | Obtiene la altura de la imagen. |
| name | Obtiene o establece el nombre de la imagen. Tenga en cuenta que si cambia el nombre de la imagen que tiene referencias en el contenido de la página, el documento puede quedar incorrecto. Por favor, use el método XImage.Rename en este caso. |
| metadata | Metadatos de la imagen. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| save(stream) | Guarda los datos de la imagen en un flujo como imagen JPEG. |
| `save(stream, format)` | Guarda la imagen en un flujo con el formato solicitado. |
| save(stream, resolution) | Guarda los datos de la imagen en un flujo como imagen JPEG con la resolución especificada. |
| save(stream, format, resolution) | Guarda la imagen en un flujo con el formato solicitado y la resolución especificada. |
| rename(name) | Renombra la imagen y reemplaza todas las referencias a la imagen con el nuevo nombre. |
| get_color_type() | Devuelve el tipo de color de la imagen. |
| detect_color_type(bmp) | Devuelve el tipo de color de la imagen. |
| is_the_same_object(image) | Devuelve true si ambas imágenes hacen referencia al mismo objeto. |
| get_name_in_collection() | Devuelve el nombre de la imagen en la colección ints. |
| to_stream() | Devuelve el flujo de imagen original. |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

