---
title: AppearanceDictionary
second_title: Referencia de API de Aspose.PDF para .NET
description: Diccionario de apariencia de la anotación que especifica cómo se presentará visualmente la anotación en la página.
type: docs
weight: 160
url: /es/net/aspose.pdf.annotations/appearancedictionary/
---
## AppearanceDictionary class

Diccionario de apariencia de la anotación que especifica cómo se presentará visualmente la anotación en la página.

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count) { get; } | Obtiene el número de elementos contenidos en el diccionario. |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize) { get; } | Obtiene un valor que indica si el diccionario tiene un tamaño fijo. |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly) { get; } | Obtiene un valor que indica si el diccionario es de solo lectura. |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized) { get; } | Obtiene un valor que indica si el acceso al diccionario está sincronizado (thread safe). |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item) { get; set; } | Representa una forma conveniente para obtener flujos de apariencia. |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys) { get; } | Obtiene claves del diccionario. Si el diccionario de apariencia tiene subdicionarios, entonces[`Keys`](./keys)contiene (N&#x7C;R&#x7C;D).valores de estado, donde N - apariencia normal, R - apariencia de rollover, D - apariencia hacia abajo y estado - el nombre del estado (por ejemplo, Activado, Desactivado para casillas de verificación). |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot) { get; } | Obtiene un objeto que se puede usar para sincronizar el acceso al diccionario. |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values) { get; } | Obtiene la lista de valores del diccionario. La colección de resultados contiene la lista de objetos XForm. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add#add)(KeyValuePair&lt;string, XForm&gt;) | Agrega par con clave y valor en el diccionario. |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add#add_2)(string, XForm) | Agregar formulario X para la clave especificada. |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear)() | Elimina todos los elementos del diccionario. |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains)(KeyValuePair&lt;string, XForm&gt;) | Comprueba si el par clave-valor especificado está contenido en el diccionario. |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey)(string) | Determina si este diccionario contiene la clave especificada. |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto#copyto)(XForm[], int) | Copia los elementos del diccionario a un Array, comenzando en un índice de Array particular. |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator)() | Devuelve un objeto IDictionaryEnumerator para el diccionario. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove#remove)(KeyValuePair&lt;string, XForm&gt;) | Elimina el par clave/valor de la colección. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove#remove_1)(string) | Elimina clave del diccionario. |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue)(string, out XForm) | Intenta encontrar la clave en el diccionario y recupera el valor si lo encuentra. |

### Ver también

* class [XForm](../../aspose.pdf/xform)
* espacio de nombres [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
