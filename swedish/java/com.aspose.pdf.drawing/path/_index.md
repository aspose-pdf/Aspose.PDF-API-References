---
title: "Path"
linktitle: "Path"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar båge."
type: docs
weight: 100
url: /sv/java/com.aspose.pdf.drawing/path/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Path, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Path

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Path extends Shape
```

Representerar båge.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Path](#Path--) | Initierar en ny instans av {@code Path} klass. |
| [Path](#Path-com.aspose.pdf.drawing.Shape:A-) | Initierar en ny instans av {@code Path} klass. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Kontrollerar om objektet passar inom de angivna behållardimensionerna (inklusive). |
| [getShapes](#getShapes--) | <p> Hämtar eller anger samlingen av former. </p> |
| [getShapesInternal](#getShapesInternal--) | Hämtar eller anger samlingen av former. |

### Path {#Path--}
```
public Path()
```

Initierar en ny instans av {@code Path} klass.

### Path {#Path-com.aspose.pdf.drawing.Shape:A-}
Initierar en ny instans av {@code Path} klass.

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

### getShapes {#getShapes--}
```
public List < Shape > getShapes()
```

<p> Hämtar eller anger samlingen av former. </p>

**Returns:**
{@code java.util.List<Shape> }objekt

### getShapesInternal {#getShapesInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< Shape > getShapesInternal()
```

Hämtar eller anger samlingen av former.

**Returns:**
intern objekt
