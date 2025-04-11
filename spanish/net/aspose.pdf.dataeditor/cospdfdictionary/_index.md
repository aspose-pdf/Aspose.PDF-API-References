---
title: Class CosPdfDictionary
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.DataEditor.CosPdfDictionary. Una clase para acceder al diccionario de un objeto
type: docs
weight: 3420
url: /es/net/aspose.pdf.dataeditor/cospdfdictionary/
---
## Clase CosPdfDictionary

Una clase para acceder al diccionario de un objeto.

```csharp
public class CosPdfDictionary : CosPdfPrimitive, IDictionary<string, ICosPdfPrimitive>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CosPdfDictionary](cospdfdictionary/)(Resources) | Crea un diccionario a partir de recursos. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/cospdfdictionary/allkeys/) { get; } | Colección completa de claves. Contiene claves editables y no editables. |
| [Count](../../aspose.pdf.dataeditor/cospdfdictionary/count/) { get; } | Obtiene el número de elementos contenidos en el `CosPdfDictionary`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/cospdfdictionary/isreadonly/) { get; } | Obtiene un valor que indica si el `CosPdfDictionary` es de solo lectura. |
| [Item](../../aspose.pdf.dataeditor/cospdfdictionary/item/) { get; set; } | Obtiene o establece el elemento con la clave especificada. |
| [Keys](../../aspose.pdf.dataeditor/cospdfdictionary/keys/) { get; } | Colección de claves editables. |
| [Values](../../aspose.pdf.dataeditor/cospdfdictionary/values/) { get; } | Obtiene un ICollection que contiene los valores en el `CosPdfDictionary`. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary)(Document) | Crea un diccionario vacío que se adjuntará al documento. |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary_1)(Page) | Crea un diccionario vacío que se adjuntará a la página. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Establece [`ICosPdfPrimitive`](../icospdfprimitive/) en el diccionario. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add_1)(string, ICosPdfPrimitive) | Establece [`ICosPdfPrimitive`](../icospdfprimitive/) en el diccionario. |
| [Clear](../../aspose.pdf.dataeditor/cospdfdictionary/clear/)() | Elimina todos los elementos del `CosPdfDictionary`. |
| [Contains](../../aspose.pdf.dataeditor/cospdfdictionary/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Determina si el `CosPdfDictionary` contiene un valor específico. |
| [ContainsKey](../../aspose.pdf.dataeditor/cospdfdictionary/containskey/)(string) | Determina si el `CosPdfDictionary` contiene un elemento con la clave especificada. |
| [CopyTo](../../aspose.pdf.dataeditor/cospdfdictionary/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/cospdfdictionary/getenumerator/)() | Devuelve un enumerador que itera a través de la colección. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Elimina la primera ocurrencia de un objeto específico del `CosPdfDictionary`. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove_1)(string) | Elimina el elemento con la clave especificada del `CosPdfDictionary`. |
| virtual [ToCosPdfBoolean](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfboolean/)() | Intenta convertir esta instancia a [`CosPdfBoolean`](../cospdfboolean/). |
| override [ToCosPdfDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/tocospdfdictionary/)() | Intenta convertir esta instancia a `CosPdfDictionary`. |
| virtual [ToCosPdfName](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfname/)() | Intenta convertir esta instancia a [`CosPdfName`](../cospdfname/). |
| virtual [ToCosPdfNumber](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfnumber/)() | Intenta convertir esta instancia a [`CosPdfNumber`](../cospdfnumber/). |
| virtual [ToCosPdfString](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfstring/)() | Intenta convertir esta instancia a [`CosPdfString`](../cospdfstring/). |
| [TryGetValue](../../aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/)(string, out ICosPdfPrimitive) | Para acceder a tipos de datos simples como cadena, nombre, booleano, número. Devuelve null para otros tipos. |

### Ver También

* clase [CosPdfPrimitive](../cospdfprimitive/)
* interfaz [ICosPdfPrimitive](../icospdfprimitive/)
* espacio de nombres [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* ensamblaje [Aspose.PDF](../../)