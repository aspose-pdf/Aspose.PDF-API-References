---
title: "Kurva"
linktitle: "Kurva"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar Bézier-kurva."
type: docs
weight: 30
url: /sv/java/com.aspose.pdf.drawing/curve/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Curve, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Curve

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Curve extends Shape
```

Representerar Bézier-kurva.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Curve](#Curve--) | Endast för intern användning |
| [Curve](#Curve-float:A-) | Initierar en ny instans av klassen {@code Curve}. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Kontrollerar om objektet passar inom de angivna behållardimensionerna (inklusive). |
| [getPositionArray](#getPositionArray--) | Hämtar en flyttalspositionsarray. |
| [setPositionArray](#setPositionArray-float:A-) | Ställer in en flyttalspositionsarray. |

### Curve {#Curve--}
```
public Curve()
```

Endast för intern användning

### Curve {#Curve-float:A-}
```
public Curve(float[] positionArray)
```

Initierar en ny instans av klassen {@code Curve}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| positionArray |  | Positionsarrayen för kontrollpunkterna på kurvan.Det bör finnas fyra kontrollpunkter,så bör längden på arrayen vara åtta. |

### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

Kontrollerar om objektet passar inom de angivna behållardimensionerna (inklusive).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
Sant om det passar; annars falskt.

### getPositionArray {#getPositionArray--}
```
public float[] getPositionArray()
```

Hämtar en flyttalspositionsarray.

**Returns:**
float[] array

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

Ställer in en flyttalspositionsarray.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | float[] array |
