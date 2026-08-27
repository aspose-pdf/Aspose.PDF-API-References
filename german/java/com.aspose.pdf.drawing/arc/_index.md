---
title: "Arc"
linktitle: "Arc"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt einen Bogen dar."
type: docs
weight: 10
url: /de/java/com.aspose.pdf.drawing/arc/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Arc, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Arc

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Arc extends Shape
```

Stellt einen Bogen dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Arc](#Arc--) | Nur für den internen Gebrauch |
| [Arc](#Arc-double-double-double-double-double-) | Initialisiert eine neue Instanz der {@code Arc} Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Überprüft, ob das Element innerhalb der angegebenen Containerabmessungen (einschließlich) passt. |
| [getAlpha](#getAlpha--) | Liefert den Fließkommawert, der den Anfangswinkelgrad des Bogens angibt. |
| [getBeta](#getBeta--) | Liefert den Fließkommawert, der den Endwinkelgrad des Bogens angibt. |
| [getPosX](#getPosX--) | Liefert den Fließkommawert, der die x-Koordinate des Zentrums des Bogens angibt. |
| [getPosY](#getPosY--) | Liefert den Fließkommawert, der die y-Koordinate des Zentrums des Bogens angibt. |
| [getRadius](#getRadius--) | Liefert den Fließkommawert, der den Radius des Bogens angibt. |
| [setAlpha](#setAlpha-double-) | Legt den Fließkommawert fest, der den Anfangswinkelgrad des Bogens angibt. |
| [setBeta](#setBeta-double-) | Legt den Fließkommawert fest, der den Endwinkelgrad des Bogens angibt. |
| [setPosX](#setPosX-double-) | Setzt den Fließkommawert, der die x-Koordinate des Zentrums des Bogens angibt. |
| [setPosY](#setPosY-double-) | Legt den Fließkommawert fest, der die y-Koordinate des Zentrums des Bogens angibt. |
| [setRadius](#setRadius-double-) | Legt den Fließkommawert fest, der den Radius des Bogens angibt. |

### Arc {#Arc--}
```
public Arc()
```

Nur für den internen Gebrauch

### Arc {#Arc-double-double-double-double-double-}
```
public Arc(double posX, double posY, double radius, double alpha, double beta)
```

Initialisiert eine neue Instanz der {@code Arc} Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| posX |  | Die x-Koordinate des Mittelpunktes des Bogens. |
| posY |  | Die y-Koordinate des Mittelpunktes des Bogens. |
| Radius |  | Der Radiuswert des Bogens. |
| alpha |  | Der Anfangswinkelwert des Bogens. |
| Beta |  | Der Endwinkelwert des Bogens. |

### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

Überprüft, ob das Element innerhalb der angegebenen Containerabmessungen (einschließlich) passt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
Wahr, wenn es passt; andernfalls falsch.

### getAlpha {#getAlpha--}
```
public double getAlpha()
```

Liefert den Fließkommawert, der den Anfangswinkelgrad des Bogens angibt.

**Returns:**
Alpha-Wert.

### getBeta {#getBeta--}
```
public double getBeta()
```

Liefert den Fließkommawert, der den Endwinkelgrad des Bogens angibt.

**Returns:**
Beta-Wert

### getPosX {#getPosX--}
```
public double getPosX()
```

Liefert den Fließkommawert, der die x-Koordinate des Zentrums des Bogens angibt.

**Returns:**
x-Koordinate des Zentrums des Bogens.

### getPosY {#getPosY--}
```
public double getPosY()
```

Liefert den Fließkommawert, der die y-Koordinate des Zentrums des Bogens angibt.

**Returns:**
y-Koordinate des Zentrums des Bogens.

### getRadius {#getRadius--}
```
public double getRadius()
```

Liefert den Fließkommawert, der den Radius des Bogens angibt.

**Returns:**
Wert, der den Radius des Bogens angibt.

### setAlpha {#setAlpha-double-}
```
public void setAlpha(double value)
```

Legt den Fließkommawert fest, der den Anfangswinkelgrad des Bogens angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Alpha-Wert. |

### setBeta {#setBeta-double-}
```
public void setBeta(double value)
```

Legt den Fließkommawert fest, der den Endwinkelgrad des Bogens angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Beta-Wert |

### setPosX {#setPosX-double-}
```
public void setPosX(double value)
```

Setzt den Fließkommawert, der die x-Koordinate des Zentrums des Bogens angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | x-Koordinate des Zentrums des Bogens. |

### setPosY {#setPosY-double-}
```
public void setPosY(double value)
```

Legt den Fließkommawert fest, der die y-Koordinate des Zentrums des Bogens angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | y-Koordinate des Zentrums des Bogens. |

### setRadius {#setRadius-double-}
```
public void setRadius(double value)
```

Legt den Fließkommawert fest, der den Radius des Bogens angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | der den Radius des Bogens angibt. |
