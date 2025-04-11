---
title: Class DestinationCollection
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.DestinationCollection. La clase representa la colección de todos los destinos de un árbol de nombres que mapea cadenas de nombres a destinos, ver 12.3.2.3 Destinos Nombrados y ver 7.7.4 Diccionario de Nombres en el documento pdf
type: docs
weight: 3510
url: /es/net/aspose.pdf/destinationcollection/
---
## Clase DestinationCollection

La clase representa la colección de todos los destinos (un árbol de nombres que mapea cadenas de nombres a destinos (ver 12.3.2.3, "Destinos Nombrados") y (ver 7.7.4, "Diccionario de Nombres")) en el documento pdf.

```csharp
public sealed class DestinationCollection : ICollection<KeyValuePair<string, object>>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.pdf/destinationcollection/count/) { get; } | Obtiene el número de elementos contenidos en la colección. |
| [IsReadOnly](../../aspose.pdf/destinationcollection/isreadonly/) { get; } | Obtiene un valor que indica si la colección es de solo lectura. |
| [Item](../../aspose.pdf/destinationcollection/item/) { get; } | Obtiene el objeto de destino por índice. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.pdf/destinationcollection/add/)(KeyValuePair&lt;string, object&gt;) | Agrega el elemento especificado. La colección es de solo lectura. Siempre lanza una excepción NotSupportedException. |
| [Clear](../../aspose.pdf/destinationcollection/clear/)() | La colección es de solo lectura. Siempre lanza una excepción NotSupportedException. |
| [Contains](../../aspose.pdf/destinationcollection/contains/)(KeyValuePair&lt;string, object&gt;) | Determina si esta instancia contiene el objeto. |
| [CopyTo](../../aspose.pdf/destinationcollection/copyto/)(KeyValuePair&lt;string, object&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/destinationcollection/getenumerator/)() | Devuelve el enumerador. |
| [GetExplicitDestination](../../aspose.pdf/destinationcollection/getexplicitdestination/)(string, bool) | Devuelve el destino explícito por el nombre. |
| [GetPageNumber](../../aspose.pdf/destinationcollection/getpagenumber/)(string, bool) | Devuelve el número de página del destino por el nombre. |
| [IndexOf](../../aspose.pdf/destinationcollection/indexof/)(KeyValuePair&lt;string, object&gt;) | Devuelve el índice del destino en la colección. |
| [Remove](../../aspose.pdf/destinationcollection/remove/)(KeyValuePair&lt;string, object&gt;) | Elimina el elemento especificado. La colección es de solo lectura. Siempre lanza una excepción NotSupportedException. |

### Ver También

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)