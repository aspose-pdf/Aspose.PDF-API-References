---
title: Class PdfXmpMetadata
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Facades.PdfXmpMetadata. Clase para manipulación con metadatos XMP
type: docs
weight: 4640
url: /es/net/aspose.pdf.facades/pdfxmpmetadata/
---
## Clase PdfXmpMetadata

Clase para manipulación con metadatos XMP.

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor)() | Constructor para PdfXmpMetadata. |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor_1)(Document) | Inicializa un nuevo objeto `PdfXmpMetadata` basado en el *documento*. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count/) { get; } | Obtiene el conteo de elementos en la colección. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtiene la fachada del documento en la que está trabajando. |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields/) { get; } | Obtiene el diccionario de campos de extensión. |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize/) { get; } | Devuelve verdadero si la colección tiene un tamaño fijo. |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly/) { get; } | Devuelve verdadero si la colección es de solo lectura. |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized/) { get; } | Devuelve verdadero si la colección está sincronizada. |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item/) { get; set; } | Obtiene o establece el valor por clave. (2 indexadores) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys/) { get; } | Obtiene las claves del diccionario. |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot/) { get; } | Obtiene el objeto de sincronización de la colección. |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values/) { get; } | Obtiene la colección de valores en el diccionario. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | Agrega un par con clave y valor al diccionario. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add)(DefaultMetadataProperties, XmpValue) | Agrega un valor a los metadatos XMP. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_4)(string, object) | Agrega un nuevo elemento al objeto diccionario. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_3)(string, XmpValue) | Agrega un nuevo elemento al objeto diccionario. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_1)(XmpPdfAExtensionObject, string, string, string) | Agrega un campo de extensión a los metadatos. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inicializa la fachada. |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear/)() | Elimina todos los elementos del objeto. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Libera Aspose.Pdf.Document vinculado con una fachada. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains)(DefaultMetadataProperties) | Verifica si el diccionario contiene la propiedad especificada. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | Verifica si el par clave-valor especificado está contenido en el diccionario. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_2)(string) | Verifica si el diccionario contiene la clave especificada. |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey/)(string) | Determina si este diccionario contiene la clave especificada. |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Libera la fachada. |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator/)() | Obtiene el objeto enumerador del diccionario. |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/)(string) | Obtiene el URI del espacio de nombres por prefijo. |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/)(string) | Obtiene el prefijo por URI del espacio de nombres. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata)() | Obtiene los metadatos XmpMetadata del pdf de entrada en formato xml. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata_1)(string) | Obtiene una parte de los metadatos XmpMetadata del pdf de entrada según un nombre de metadato. |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/)(string, string) | Registra el URI del espacio de nombres. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_2)(DefaultMetadataProperties) | Elimina el elemento con la clave especificada. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Elimina el par clave/valor de la colección. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_1)(string) | Elimina la clave del diccionario. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Guarda el documento PDF en el flujo especificado. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Guarda el documento PDF en el archivo especificado. |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue/)(string, out XmpValue) | Intenta encontrar la clave en el diccionario y recupera el valor si se encuentra. |

### Ver También

* clase [SaveableFacade](../saveablefacade/)
* clase [XmpValue](../../aspose.pdf/xmpvalue/)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../)