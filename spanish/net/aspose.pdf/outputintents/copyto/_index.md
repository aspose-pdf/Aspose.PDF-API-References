---
title: OutputIntents.CopyTo
second_title: Aspose.PDF for .NET API Reference
description: Método OutputIntents. Copia los elementos de la colección al array comenzando en el arrayIndex particular en el array
type: docs
weight: 70
url: /es/net/aspose.pdf/outputintents/copyto/
---
## Método OutputIntents.CopyTo

Copia los elementos de la colección al *array*, comenzando en el *arrayIndex* particular en el array.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | OutputIntent[] | El array unidimensional que es el destino de los intents de salida copiados de la colección. El array debe tener indexación basada en cero. |
| arrayIndex | Int32 | El índice basado en cero en el *array* en el que comienza la copia. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *array* es nulo. |
| ArgumentOutOfRangeException | *arrayIndex* es menor que 0. |
| ArgumentException | El número de elementos en la fuente [`OutputIntents`](../) es mayor que el espacio disponible desde *arrayIndex* hasta el final del *array* de destino. |

### Véase También

* clase [OutputIntent](../../outputintent/)
* clase [OutputIntents](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)