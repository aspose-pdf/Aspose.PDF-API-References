---
title: "Kreis"
linktitle: "Kreis"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt einen Kreis dar."
type: docs
weight: 20
url: /de/java/com.aspose.pdf.drawing/circle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Circle, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Circle

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Circle extends Shape
```

Stellt einen Kreis dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Circle](#Circle--) | Nur für den internen Gebrauch |
| [Circle](#Circle-float-float-float-) | Initialisiert eine neue Instanz der {@code Circle}-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Überprüft, ob das Element innerhalb der angegebenen Containerabmessungen (einschließlich) passt. |
| [getPosX](#getPosX--) | Liefert den Fließkommawert, der die x-Koordinate des Zentrums des Bogens angibt. |
| [getPosY](#getPosY--) | Liefert den Fließkommawert, der die y-Koordinate des Zentrums des Bogens angibt. |
| [getRadius](#getRadius--) | Liefert den Fließkommawert, der den Radius des Kreises angibt. |
| [setPosX](#setPosX-double-) | Setzt den Fließkommawert, der die x-Koordinate des Zentrums des Bogens angibt. |
| [setPosY](#setPosY-double-) | Legt den Fließkommawert fest, der die y-Koordinate des Zentrums des Bogens angibt. |
| [setRadius](#setRadius-double-) | Legt den Fließkommawert fest, der den Radius des Kreises angibt. |

### Circle {#Circle--}
```
public Circle()
```

Nur für den internen Gebrauch

### Circle {#Circle-float-float-float-}
```
public Circle(float posX, float posY, float radius)
```

Initialisiert eine neue Instanz der {@code Circle}-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| posX |  | Die x-Koordinate des Zentrums des Kreises. |
| posY |  | Die y-Koordinate des Zentrums des Kreises. |
| Radius |  | Der Radius des Kreises. |

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

Liefert den Fließkommawert, der den Radius des Kreises angibt.

**Returns:**
Wert, der den Radius des Kreises angibt.

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

Legt den Fließkommawert fest, der den Radius des Kreises angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | der den Radius des Kreises angibt. |
