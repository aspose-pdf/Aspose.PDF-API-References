---
title: Enum LineJoin
second_title: Aspose.PDF for .NET API Reference
description: Enum LineJoin de Aspose.Pdf.Operators. El estilo de unión de líneas especificará la forma que se utilizará en las esquinas de los caminos que son trazados
type: docs
weight: 7450
url: /es/net/aspose.pdf.operators/linejoin/
---
## Enumeración LineJoin

El estilo de unión de líneas especificará la forma que se utilizará en las esquinas de los caminos que son trazados.

```csharp
public enum LineJoin
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| MiterJoin | `0` | Unión en inglete. Los bordes exteriores de los trazos de los dos segmentos se extenderán hasta que se encuentren en un ángulo, como en un marco de imagen. Si los segmentos se encuentran en un ángulo demasiado agudo según lo definido por el parámetro de límite de inglete (ver 8.4.3.5, "Límite de Inglete"), se utilizará en su lugar una unión biselada. |
| RoundJoin | `1` | Unión redonda. Se dibujará un arco de un círculo con un diámetro igual al ancho de la línea alrededor del punto donde se encuentran los dos segmentos, conectando los bordes exteriores de los trazos de los dos segmentos. Esta figura en forma de porción de pastel se llenará, produciendo una esquina redondeada. |
| BevelJoin | `2` | Unión biselada. Los dos segmentos se terminarán con tapas planas (ver 8.4.3.3, "Estilo de tapa de línea") y la muesca resultante más allá de los extremos de los segmentos se llenará con un triángulo. |

### Ver También

* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)