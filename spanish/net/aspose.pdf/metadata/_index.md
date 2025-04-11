---
title: Class Metadata
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Metadata. Proporciona acceso a la secuencia de metadatos XMP
type: docs
weight: 6950
url: /es/net/aspose.pdf/metadata/
---
## Clase Metadata

Proporciona acceso a la secuencia de metadatos XMP.

```csharp
public sealed class Metadata : IDictionary<string, XmpValue>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.pdf/metadata/count/) { get; } | Obtiene el conteo de elementos en la colección. |
| [ExtensionFields](../../aspose.pdf/metadata/extensionfields/) { get; } | Obtiene el diccionario de campos de extensión. |
| [IsFixedSize](../../aspose.pdf/metadata/isfixedsize/) { get; } | Verifica si la colección tiene un tamaño fijo. |
| [IsReadOnly](../../aspose.pdf/metadata/isreadonly/) { get; } | Verifica si la colección es de solo lectura. |
| [IsSynchronized](../../aspose.pdf/metadata/issynchronized/) { get; } | Verifica si la colección está sincronizada. |
| [Item](../../aspose.pdf/metadata/item/) { get; set; } | Obtiene o establece datos de los metadatos. |
| [Keys](../../aspose.pdf/metadata/keys/) { get; } | Obtiene la colección de claves de metadatos. |
| [NamespaceManager](../../aspose.pdf/metadata/namespacemanager/) { get; } | Obtiene el administrador de espacios de nombres. |
| [SyncRoot](../../aspose.pdf/metadata/syncroot/) { get; } | Obtiene el objeto de sincronización de la colección. |
| [Values](../../aspose.pdf/metadata/values/) { get; } | Obtiene los valores en los metadatos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.pdf/metadata/add/#add)(KeyValuePair&lt;string, XmpValue&gt;) | Agrega un par con clave y valor al diccionario. |
| [Add](../../aspose.pdf/metadata/add/#add_3)(string, object) | Agrega un valor a los metadatos. |
| [Add](../../aspose.pdf/metadata/add/#add_1)(string, XmpPdfAExtensionObject) | Agrega una extensión pdf a los metadatos. |
| [Add](../../aspose.pdf/metadata/add/#add_2)(string, XmpValue) | Agrega un valor a los metadatos. |
| [Clear](../../aspose.pdf/metadata/clear/)() | Limpia los metadatos. |
| [Contains](../../aspose.pdf/metadata/contains/#contains)(KeyValuePair&lt;string, XmpValue&gt;) | Verifica si el par clave-valor especificado está contenido en el diccionario. |
| [Contains](../../aspose.pdf/metadata/contains/#contains_1)(string) | Verifica si la clave está contenida en los metadatos. |
| [ContainsKey](../../aspose.pdf/metadata/containskey/)(string) | Determina si este diccionario contiene la clave especificada. |
| [CopyTo](../../aspose.pdf/metadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/metadata/getenumerator/)() | Devuelve el enumerador del diccionario. |
| [GetNamespaceUriByPrefix](../../aspose.pdf/metadata/getnamespaceuribyprefix/)(string) | Devuelve el URI del espacio de nombres por prefijo. |
| [GetPrefixByNamespaceUri](../../aspose.pdf/metadata/getprefixbynamespaceuri/)(string) | Devuelve el prefijo por URI del espacio de nombres. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri)(string, string) | Registra el URI del espacio de nombres. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri_1)(string, string, string) | Registra el URI del espacio de nombres. |
| [Remove](../../aspose.pdf/metadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Elimina el par clave/valor de la colección. |
| [Remove](../../aspose.pdf/metadata/remove/#remove_1)(string) | Elimina la entrada de los metadatos. |
| [TryGetValue](../../aspose.pdf/metadata/trygetvalue/)(string, out XmpValue) | Intenta encontrar la clave en el diccionario y recupera el valor si se encuentra. |

### Ver También

* clase [XmpValue](../xmpvalue/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)