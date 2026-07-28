---
title: "LineJoin"
linktitle: "LineJoin"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "El estilo de unión de línea debe especificar la forma que se usará en las esquinas de los trazados que se dibujan."
type: docs
weight: 370
url: /es/java/com.aspose.pdf.operators/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.operators.LineJoin, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.operators.LineJoin, com.aspose.ms.System.Enum, com.aspose.pdf.operators.LineJoin

```
public final class LineJoin extends com.aspose.ms.System.Enum
```

El estilo de unión de línea debe especificar la forma que se usará en las esquinas de los trazados que se dibujan.

## Campos

| Campo | Descripción |
| --- | --- |
| [BevelJoin](#BevelJoin) | Unión biselada. Los dos segmentos se completarán con tapones planos (ver 8.4.3.3, "Line Cap Style") y la muesca resultante más allá de los extremos de los segmentos se rellenará con un triángulo. |
| [MiterJoin](#MiterJoin) | Unión en inglete. Los bordes exteriores de los trazos de los dos segmentos se extenderán hasta encontrarse en un ángulo, como en un marco de foto. Si los segmentos se encuentran en un ángulo demasiado agudo según lo definido por el parámetro de límite de inglete (ver 8.4.3.5, "Miter Limit"), se usará una unión biselada en su lugar. |
| [RoundJoin](#RoundJoin) | Unión redondeada. Se dibujará un arco de círculo con un diámetro igual al ancho de línea alrededor del punto donde se encuentran los dos segmentos, conectando los bordes exteriores de los trazos de los dos segmentos. Esta figura en forma de porción de pastel se rellenará, produciendo una esquina redondeada. |

### BevelJoin {#BevelJoin}
```
public static final int BevelJoin
```

Unión biselada. Los dos segmentos se completarán con tapones planos (ver 8.4.3.3, "Line Cap Style") y la muesca resultante más allá de los extremos de los segmentos se rellenará con un triángulo.

### MiterJoin {#MiterJoin}
```
public static final int MiterJoin
```

Unión en inglete. Los bordes exteriores de los trazos de los dos segmentos se extenderán hasta encontrarse en un ángulo, como en un marco de foto. Si los segmentos se encuentran en un ángulo demasiado agudo según lo definido por el parámetro de límite de inglete (ver 8.4.3.5, "Miter Limit"), se usará una unión biselada en su lugar.

### RoundJoin {#RoundJoin}
```
public static final int RoundJoin
```

Unión redondeada. Se dibujará un arco de círculo con un diámetro igual al ancho de línea alrededor del punto donde se encuentran los dos segmentos, conectando los bordes exteriores de los trazos de los dos segmentos. Esta figura en forma de porción de pastel se rellenará, produciendo una esquina redondeada.
