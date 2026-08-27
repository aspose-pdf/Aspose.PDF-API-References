---
title: "Rectangle"
linktitle: "Rectangle"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar rektangel."
type: docs
weight: 120
url: /sv/java/com.aspose.pdf.drawing/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Rectangle, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Rectangle

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Rectangle extends Shape
```

Representerar rektangel.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Rectangle](#Rectangle--) | Konstruktör |
| [Rectangle](#Rectangle-float-float-float-float-) | Initierar en ny instans av klassen {@code Rectangle}. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Kontrollerar om objektet passar inom de angivna behållardimensionerna (inklusive). |
| [getBottom](#getBottom--) | Hämtar ett flyttalsvärde som indikerar rektangelns nedre position. |
| [getHeight](#getHeight--) | Hämtar ett flyttalsvärde som indikerar rektangelns höjd. |
| [getLeft](#getLeft--) | Hämtar ett flyttalsvärde som indikerar rektangelns vänstra position. |
| [getRoundedCornerRadius](#getRoundedCornerRadius--) | Hämtar ett flyttalsvärde som indikerar radien på rektangelns hörn. |
| [getWidth](#getWidth--) | Hämtar ett flyttalsvärde som indikerar rektangelns bredd. |
| [setBottom](#setBottom-double-) | Ställer in ett flyttalsvärde som indikerar rektangelns nedre position. |
| [setHeight](#setHeight-double-) | Ställer in ett flyttalsvärde som indikerar rektangelns höjd. |
| [setLeft](#setLeft-double-) | Ställer in ett flyttalsvärde som indikerar rektangelns vänstra position. |
| [setRoundedCornerRadius](#setRoundedCornerRadius-double-) | Ställer in ett flyttalsvärde som indikerar radien på rektangelns hörn. |
| [setWidth](#setWidth-double-) | Ställer in flyttalvärde som anger rektangelns bredd. |

### Rectangle {#Rectangle--}
```
public Rectangle()
```

Konstruktör

### Rectangle {#Rectangle-float-float-float-float-}
```
public Rectangle(float left, float bottom, float width, float height)
```

Initierar en ny instans av klassen {@code Rectangle}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster |  | Den vänstra positionen för rektangeln. |
| nedre |  | Den nedre positionen för rektangeln. |
| bredd |  | Rektangelns bredd. |
| höjd |  | Rektangelns höjd. |

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

### getBottom {#getBottom--}
```
public double getBottom()
```

Hämtar ett flyttalsvärde som indikerar rektangelns nedre position.

**Returns:**
värde som anger den nedre positionen för rektangeln.

### getHeight {#getHeight--}
```
public double getHeight()
```

Hämtar ett flyttalsvärde som indikerar rektangelns höjd.

**Returns:**
värde som anger rektangelns höjd.

### getLeft {#getLeft--}
```
public double getLeft()
```

Hämtar ett flyttalsvärde som indikerar rektangelns vänstra position.

**Returns:**
flyttalvärde som anger den vänstra positionen för rektangeln.

### getRoundedCornerRadius {#getRoundedCornerRadius--}
```
public double getRoundedCornerRadius()
```

Hämtar ett flyttalsvärde som indikerar radien på rektangelns hörn.

**Returns:**
värde som anger radien på rektangelns hörn.

### getWidth {#getWidth--}
```
public double getWidth()
```

Hämtar ett flyttalsvärde som indikerar rektangelns bredd.

**Returns:**
värde som anger rektangelns bredd.

### setBottom {#setBottom-double-}
```
public void setBottom(double value)
```

Ställer in ett flyttalsvärde som indikerar rektangelns nedre position.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | värde som anger den nedre positionen för rektangeln. |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Ställer in ett flyttalsvärde som indikerar rektangelns höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | värde som anger rektangelns höjd. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Ställer in ett flyttalsvärde som indikerar rektangelns vänstra position.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalvärde som anger den vänstra positionen för rektangeln. |

### setRoundedCornerRadius {#setRoundedCornerRadius-double-}
```
public void setRoundedCornerRadius(double value)
```

Ställer in ett flyttalsvärde som indikerar radien på rektangelns hörn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | som anger radien på rektangelns hörn. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Ställer in flyttalvärde som anger rektangelns bredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | som anger rektangelns bredd. |
