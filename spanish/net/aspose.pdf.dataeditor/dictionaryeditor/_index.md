---
title: Class DictionaryEditor
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.DataEditor.DictionaryEditor. Una clase para acceder al diccionario de árbol de un documento, diccionario de documento, diccionario de página, diccionario de recursos.
type: docs
weight: 3470
url: /es/net/aspose.pdf.dataeditor/dictionaryeditor/
---
## Clase DictionaryEditor

Una clase para acceder al diccionario de árbol de un documento (diccionario de documento, diccionario de página, diccionario de recursos).

```csharp
public class DictionaryEditor : IDictionary<string, ICosPdfPrimitive>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DictionaryEditor](dictionaryeditor/#constructor)(Document) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_1)(Page) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_2)(Resources) |  |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/dictionaryeditor/allkeys/) { get; } | Colección completa de claves. Contiene claves editables y no editables. |
| [Count](../../aspose.pdf.dataeditor/dictionaryeditor/count/) { get; } | Obtiene el número de elementos contenidos en el `DictionaryEditor`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/dictionaryeditor/isreadonly/) { get; } | Obtiene un valor que indica si el `DictionaryEditor` es de solo lectura. |
| [Item](../../aspose.pdf.dataeditor/dictionaryeditor/item/) { get; set; } | Obtiene o establece el elemento con la clave especificada. |
| [Keys](../../aspose.pdf.dataeditor/dictionaryeditor/keys/) { get; } | Colección de claves editables. |
| [Values](../../aspose.pdf.dataeditor/dictionaryeditor/values/) { get; } | Obtiene un ICollection que contiene los valores en el `DictionaryEditor`. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Establece [`ICosPdfPrimitive`](../icospdfprimitive/) en el diccionario. |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add_1)(string, ICosPdfPrimitive) | Establece [`ICosPdfPrimitive`](../icospdfprimitive/) en el diccionario. |
| [Clear](../../aspose.pdf.dataeditor/dictionaryeditor/clear/)() | Elimina todos los elementos del `DictionaryEditor`. |
| [Contains](../../aspose.pdf.dataeditor/dictionaryeditor/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Determina si el `DictionaryEditor` contiene un valor específico. |
| [ContainsKey](../../aspose.pdf.dataeditor/dictionaryeditor/containskey/)(string) | Determina si el `DictionaryEditor` contiene un elemento con la clave especificada. |
| [CopyTo](../../aspose.pdf.dataeditor/dictionaryeditor/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/dictionaryeditor/getenumerator/)() | Devuelve un enumerador que itera a través de la colección. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Elimina la primera ocurrencia de un objeto específico del `DictionaryEditor`. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove_1)(string) | Elimina el elemento con la clave especificada del `DictionaryEditor`. |
| [TryGetValue](../../aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/)(string, out ICosPdfPrimitive) | Para acceso a tipos de datos simples como string, nombre, bool, número. Devuelve null para otros tipos. |

### Ver También

* interfaz [ICosPdfPrimitive](../icospdfprimitive/)
* espacio de nombres [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* ensamblaje [Aspose.PDF](../../)