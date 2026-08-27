---
title: "Linje"
linktitle: "Linje"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar linje."
type: docs
weight: 90
url: /sv/java/com.aspose.pdf.drawing/line/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Line, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Line

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Line extends Shape
```

Representerar linje.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Line](#Line--) | Endast för intern användning |
| [Line](#Line-float:A-) | Initierar en ny instans av {@code Line}-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Kontrollerar om objektet passar inom de angivna behållardimensionerna (inklusive). |
| [getPositionArray](#getPositionArray--) | Hämtar objekt som indikerar positionsarrayen. Arrayen är sammansatt av koordinater för varje kontrollpunkt på linjen. direkt. |
| [setPositionArray](#setPositionArray-float:A-) | Ställer in objekt som indikerar positionsarrayen. Arrayen är sammansatt av koordinater för varje kontrollpunkt på linjen. direkt. |

### Line {#Line--}
```
public Line()
```

Endast för intern användning

### Line {#Line-float:A-}
```
public Line(float[] positionArray)
```

Initierar en ny instans av {@code Line}-klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| positionArray |  | Linjens positionsarray. |

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

Hämtar objekt som indikerar positionsarrayen. Arrayen är sammansatt av koordinater för varje kontrollpunkt på linjen. direkt.

**Returns:**
som indikerar positionsarrayen.

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

Ställer in objekt som indikerar positionsarrayen. Arrayen är sammansatt av koordinater för varje kontrollpunkt på linjen. direkt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | som indikerar positionsarrayen. |
