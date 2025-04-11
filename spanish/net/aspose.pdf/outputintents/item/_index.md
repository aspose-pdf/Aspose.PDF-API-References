---
title: OutputIntents.Item
second_title: Aspose.PDF for .NET API Reference
description: Propiedad OutputIntents. Obtiene la intención de salida en el índice especificado
type: docs
weight: 30
url: /es/net/aspose.pdf/outputintents/item/
---
## Indexador de OutputIntents

Obtiene la intención de salida en el *índice* especificado.

```csharp
public OutputIntent this[int index] { get; }
```

| Parámetro | Descripción |
| --- | --- |
| index | El índice basado en cero de la intención de salida a obtener. |

### Valor de Retorno

La intención de salida en el *índice* especificado.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *index* es menor que 0 o *index* es igual o mayor que [`Count`](../count/). |
| InvalidOperationException | El documento que contiene la colección no tiene un catálogo para acceder a las OutputIntents. |

### Véase También

* clase [OutputIntent](../../outputintent/)
* clase [OutputIntents](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)