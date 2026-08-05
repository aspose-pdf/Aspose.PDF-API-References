---
title: "XImageCollection"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase que representa una colección de XImage."
type: docs
weight: 1690
url: /es/python-net/aspose.pdf/ximagecollection/
---

## XImageCollection class

Clase que representa una colección de XImage.

El tipo XImageCollection expone los siguientes miembros:
## Propiedades
| Nombre | Descripción |
| :- | :- |
| is_synchronized | Devuelve true si el objeto está sincronizado. |
| sync_root | Devuelve el objeto de sincronización. |
| names | Obtiene la matriz de nombres de imágenes. |
## Indexer
| Nombre | Descripción |
| :- | :- |
| [index] | Obtiene la imagen de la colección por su índice. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| add(image) | Agrega una nueva imagen a la lista de imágenes. Este método agrega la imagen como referencia al mismo PdfObject (lo que permite reducir el tamaño del archivo) |
| add(image) | Agrega la entidad al final de la colección, de modo que la entidad pueda ser accedida por el último índice. |
| add(image, filter_type) | Agrega la entidad al final de la colección, de modo que la entidad pueda ser accedida por el último índice. |
| add(image, quality) | Agrega la entidad al final de la colección, de modo que la entidad pueda ser accedida por el último índice. |
| delete(index) | Elimina el índice de la colección por índice. |
| delete(index, action) | Elimina la imagen de la colección por índice ejecutando la acción especificada por el parámetro action. |
| delete(name) | Elimina el elemento de la colección por nombre. |
| delete(name, action) | Elimina el elemento de la colección por nombre. |
| delete() | Elimina el índice de la colección por índice. |
| replace(index, stream) | Reemplaza la imagen en la colección con otra imagen. |
| replace(index, stream, quality, is_black_and_white) | Reemplaza la imagen en la colección con otra imagen. |
| replace(index, stream, quality) | Reemplaza la imagen en la colección con otra imagen. |
| get_image_name(image) | Devuelve el nombre en la lista de imágenes que es la clave de la imagen dada. |

### Ver también

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

