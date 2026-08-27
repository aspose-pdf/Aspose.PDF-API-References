---
title: "Ellips"
linktitle: "Ellips"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar ellips."
type: docs
weight: 40
url: /sv/java/com.aspose.pdf.drawing/ellipse/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Ellipse, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Ellipse

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Ellipse extends Shape
```

Representerar ellips.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Ellipse](#Ellipse--) | Endast för intern användning |
| [Ellipse](#Ellipse-double-double-double-double-) | Initierar en ny instans av klassen {@code Ellipse}. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Kontrollerar om objektet passar inom de angivna behållardimensionerna (inklusive). |
| [getBottom](#getBottom--) | Hämtar flyttalvärde som anger den nedre positionen för ellipsen. |
| [getHeight](#getHeight--) | Hämtar flyttalvärde som anger höjden på ellipsen. |
| [getLeft](#getLeft--) | Hämtar flyttalvärde som anger den vänstra positionen för ellipsen. |
| [getWidth](#getWidth--) | Hämtar flyttalvärde som anger bredden på ellipsen. |
| [setBottom](#setBottom-double-) | Ställer in flyttalvärde som anger den nedre positionen för ellipsen. |
| [setHeight](#setHeight-double-) | Ställer in flyttalvärde som anger höjden på ellipsen. |
| [setLeft](#setLeft-double-) | Ställer in flyttalvärde som anger den vänstra positionen för ellipsen. |
| [setWidth](#setWidth-double-) | Hämtar flyttalvärde som anger bredden på ellipsen. |

### Ellipse {#Ellipse--}
```
public Ellipse()
```

Endast för intern användning

### Ellipse {#Ellipse-double-double-double-double-}
```
public Ellipse(double left, double bottom, double width, double height)
```

Initierar en ny instans av klassen {@code Ellipse}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster |  | Den vänstra positionen för ellipsen. |
| nedre |  | Den nedre positionen för ellipsen. |
| bredd |  | Bredden på ellipsen. |
| höjd |  | Höjden på ellipsen. |

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

Hämtar flyttalvärde som anger den nedre positionen för ellipsen.

**Returns:**
värde som anger den nedre positionen för ellipsen.

### getHeight {#getHeight--}
```
public double getHeight()
```

Hämtar flyttalvärde som anger höjden på ellipsen.

**Returns:**
värde som anger höjden på ellipsen

### getLeft {#getLeft--}
```
public double getLeft()
```

Hämtar flyttalvärde som anger den vänstra positionen för ellipsen.

**Returns:**
värde som anger den vänstra positionen för ellipsen.

### getWidth {#getWidth--}
```
public double getWidth()
```

Hämtar flyttalvärde som anger bredden på ellipsen.

**Returns:**
värde som anger bredden på ellipsen.

### setBottom {#setBottom-double-}
```
public void setBottom(double value)
```

Ställer in flyttalvärde som anger den nedre positionen för ellipsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | som anger den nedre positionen för ellipsen. |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Ställer in flyttalvärde som anger höjden på ellipsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | som anger höjden på ellipsen |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Ställer in flyttalvärde som anger den vänstra positionen för ellipsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | som indikerar ellipsens vänstra position. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Hämtar flyttalvärde som anger bredden på ellipsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | som indikerar ellipsens bredd. |
