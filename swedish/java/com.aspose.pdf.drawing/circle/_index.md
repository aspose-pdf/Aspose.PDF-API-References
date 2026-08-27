---
title: "Cirkel"
linktitle: "Cirkel"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar cirkel."
type: docs
weight: 20
url: /sv/java/com.aspose.pdf.drawing/circle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Circle, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Circle

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Circle extends Shape
```

Representerar cirkel.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Circle](#Circle--) | Endast för intern användning |
| [Circle](#Circle-float-float-float-) | Initierar en ny instans av {@code Circle}-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Kontrollerar om objektet passar inom de angivna behållardimensionerna (inklusive). |
| [getPosX](#getPosX--) | Hämtar flyttalvärde som anger x-koordinaten för bågens centrum. |
| [getPosY](#getPosY--) | Hämtar flyttalvärde som anger y-koordinaten för bågens centrum. |
| [getRadius](#getRadius--) | Hämtar flyttalvärde som anger cirkelns radie. |
| [setPosX](#setPosX-double-) | Ställer in flyttalvärde som anger x-koordinaten för bågens centrum. |
| [setPosY](#setPosY-double-) | Ställer in flyttalvärde som anger y-koordinaten för bågens centrum. |
| [setRadius](#setRadius-double-) | Ställer in flyttalvärde som anger cirkelns radie. |

### Circle {#Circle--}
```
public Circle()
```

Endast för intern användning

### Circle {#Circle-float-float-float-}
```
public Circle(float posX, float posY, float radius)
```

Initierar en ny instans av {@code Circle}-klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| posX |  | x-koordinaten för cirkelns centrum. |
| posY |  | y-koordinaten för cirkelns centrum. |
| radius |  | Radien på cirkeln. |

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

### getPosX {#getPosX--}
```
public double getPosX()
```

Hämtar flyttalvärde som anger x-koordinaten för bågens centrum.

**Returns:**
x-koordinaten för bågens centrum.

### getPosY {#getPosY--}
```
public double getPosY()
```

Hämtar flyttalvärde som anger y-koordinaten för bågens centrum.

**Returns:**
y-koordinaten för bågens centrum.

### getRadius {#getRadius--}
```
public double getRadius()
```

Hämtar flyttalvärde som anger cirkelns radie.

**Returns:**
värde som indikerar radien på cirkeln.

### setPosX {#setPosX-double-}
```
public void setPosX(double value)
```

Ställer in flyttalvärde som anger x-koordinaten för bågens centrum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | x-koordinaten för bågens centrum. |

### setPosY {#setPosY-double-}
```
public void setPosY(double value)
```

Ställer in flyttalvärde som anger y-koordinaten för bågens centrum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | y-koordinaten för bågens centrum. |

### setRadius {#setRadius-double-}
```
public void setRadius(double value)
```

Ställer in flyttalvärde som anger cirkelns radie.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | som indikerar radien på cirkeln. |
