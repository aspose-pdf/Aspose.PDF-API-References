---
title: "Arc"
linktitle: "Arc"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar båge."
type: docs
weight: 10
url: /sv/java/com.aspose.pdf.drawing/arc/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Arc, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Arc

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Arc extends Shape
```

Representerar båge.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Arc](#Arc--) | Endast för intern användning |
| [Arc](#Arc-double-double-double-double-double-) | Initierar en ny instans av klassen {@code Arc}. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Kontrollerar om objektet passar inom de angivna behållardimensionerna (inklusive). |
| [getAlpha](#getAlpha--) | Hämtar float value som indikerar startvinkeln i grader för bågen. |
| [getBeta](#getBeta--) | Hämtar float value som indikerar slutvinkeln i grader för bågen. |
| [getPosX](#getPosX--) | Hämtar flyttalvärde som anger x-koordinaten för bågens centrum. |
| [getPosY](#getPosY--) | Hämtar flyttalvärde som anger y-koordinaten för bågens centrum. |
| [getRadius](#getRadius--) | Hämtar float value som indikerar radien för bågen. |
| [setAlpha](#setAlpha-double-) | Sätter float value som indikerar startvinkeln i grader för bågen. |
| [setBeta](#setBeta-double-) | Sätter float value som indikerar slutvinkeln i grader för bågen. |
| [setPosX](#setPosX-double-) | Ställer in flyttalvärde som anger x-koordinaten för bågens centrum. |
| [setPosY](#setPosY-double-) | Ställer in flyttalvärde som anger y-koordinaten för bågens centrum. |
| [setRadius](#setRadius-double-) | Sätter float value som indikerar radien för bågen. |

### Arc {#Arc--}
```
public Arc()
```

Endast för intern användning

### Arc {#Arc-double-double-double-double-double-}
```
public Arc(double posX, double posY, double radius, double alpha, double beta)
```

Initierar en ny instans av klassen {@code Arc}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| posX |  | x-koordinaten för bågens mittpunkt. |
| posY |  | y-koordinaten för bågens mittpunkt. |
| radius |  | Radievärdet för bågen. |
| alpha |  | Startvinkelvärdet för bågen. |
| beta |  | Värdet för slutvinkeln på bågen. |

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

### getAlpha {#getAlpha--}
```
public double getAlpha()
```

Hämtar float value som indikerar startvinkeln i grader för bågen.

**Returns:**
alfavärde.

### getBeta {#getBeta--}
```
public double getBeta()
```

Hämtar float value som indikerar slutvinkeln i grader för bågen.

**Returns:**
betavärde

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

Hämtar float value som indikerar radien för bågen.

**Returns:**
värde som anger radien på bågen.

### setAlpha {#setAlpha-double-}
```
public void setAlpha(double value)
```

Sätter float value som indikerar startvinkeln i grader för bågen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | alfavärde. |

### setBeta {#setBeta-double-}
```
public void setBeta(double value)
```

Sätter float value som indikerar slutvinkeln i grader för bågen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | betavärde |

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

Sätter float value som indikerar radien för bågen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | som anger radien på bågen. |
