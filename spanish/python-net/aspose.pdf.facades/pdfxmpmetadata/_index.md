---
title: "PdfXmpMetadata"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Clase para la manipulación de metadatos XMP."
type: docs
weight: 380
url: /es/python-net/aspose.pdf.facades/pdfxmpmetadata/
---

## PdfXmpMetadata class

Clase para la manipulación de metadatos XMP.

El tipo PdfXmpMetadata expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| PdfXmpMetadata() | Constructor para PdfXmpMetadata. |
| PdfXmpMetadata(document) | Inicializa una nueva instancia de la clase PdfXmpMetadata |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| document | Obtiene la fachada del documento en la que está trabajando. |
| keys | Obtiene las claves del diccionario. |
| values | Obtiene la colección de valores del diccionario. |
| is_fixed_size | Devuelve true si la colección tiene tamaño fijo. |
| is_synchronized | Devuelve true si la colección está sincronizada. |
| sync_root | Obtiene el objeto de sincronización de la colección. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| bind_pdf(src_file) | Vincula el documento PDF para su edición. |
| bind_pdf(src_stream) | Vincula el documento PDF para su edición. |
| bind_pdf(src_doc) | Vincula el documento PDF para su edición. |
| save(dest_file) | Guarda el documento PDF en el archivo especificado. |
| save(dest_stream) | Guarda el documento PDF en el flujo especificado. |
| add(key, value) | Agrega un valor a los metadatos XMP. |
| add(xmp_pdf_a_extension_object, namespace_prefix, namespace_uri, schema_description) | Agrega un campo de extensión a los metadatos. |
| add(key, value) | Agrega un nuevo elemento al objeto diccionario. |
| add(key, value) | Agrega un campo de extensión a los metadatos. |
| remove(key) | Elimina el elemento con la clave especificada. |
| remove(key) | Elimina la clave del diccionario. |
| contains(key) | Comprueba si el diccionario contiene la clave especificada. |
| contains(property) | Comprueba si el diccionario contiene la propiedad especificada. |
| get_xmp_metadata() | Obtén los XmpMetadata del PDF de entrada en formato XML. |
| get_xmp_metadata(name) | Obtenga una parte del XmpMetadata del PDF de entrada según un nombre de meta. |
| close() | Libera cualquier recurso asociado con la fachada actual. |
| register_namespace_uri(prefix, namespace_uri) | Registra el URI del espacio de nombres. |
| get_namespace_uri_by_prefix(prefix) | Obtiene el URI del espacio de nombres por prefijo. |
| get_prefix_by_namespace_uri(namespace_uri) | Obtiene el prefijo por URI del espacio de nombres. |
| contains_key(key) | Determina si este diccionario contiene la clave especificada. |
| try_get_value(key, value) | Intenta encontrar la clave en el diccionario y recupera el valor si se encuentra. |

### Ver también

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

