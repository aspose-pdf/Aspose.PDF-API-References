---
title: "Punkt"
linktitle: "Punkt"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt einen Punkt mit Bruchkoordinaten dar."
type: docs
weight: 3870
url: /de/java/com.aspose.pdf/point/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Point

```
public final class Point extends Object
```

Stellt einen Punkt mit Bruchkoordinaten dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Point](#Point-double-double-) | Initialisiert eine neue Instanz von {@code Point}. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [distance](#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Berechnet die Entfernung zwischen zwei Punkten. |
| [getTrivial](#getTrivial--) | Liefert den Punkt mit Nullkoordinaten. |
| [getX](#getX--) | Liefert den X-Koordinatenwert. |
| [getY](#getY--) | Liefert den Y-Koordinatenwert. |
| [setX](#setX-double-) | Setzt den X-Koordinatenwert. |
| [setY](#setY-double-) | Setzt den Y-Koordinatenwert. |
| [toPoint](#toPoint--) | Konvertiert den Punkt in ein java.awt.geom.Point2D.Float-Objekt. |
| [toString](#toString--) | Gibt die Zeichenkettenrepräsentation des aktuellen Punktes zurück. |

### Point {#Point-double-double-}
```
public Point(double x, double y)
```

Initialisiert eine neue Instanz von {@code Point}.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x |  | x-Koordinatenwert. |
| y |  | y-Koordinatenwert. |

### distance {#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Berechnet die Entfernung zwischen zwei Punkten.

### getTrivial {#getTrivial--}
```
public static Point getTrivial()
```

Liefert den Punkt mit Nullkoordinaten.

**Returns:**
Point-Objekt

### getX {#getX--}
```
public double getX()
```

Liefert den X-Koordinatenwert.

**Returns:**
double-Wert

### getY {#getY--}
```
public double getY()
```

Liefert den Y-Koordinatenwert.

**Returns:**
double-Wert

### setX {#setX-double-}
```
public void setX(double value)
```

Setzt den X-Koordinatenwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setY {#setY-double-}
```
public void setY(double value)
```

Setzt den Y-Koordinatenwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### toPoint {#toPoint--}
```
public Point2D.Float toPoint()
```

Konvertiert den Punkt in ein java.awt.geom.Point2D.Float-Objekt.

**Returns:**
Float-Struktur.

### toString {#toString--}
```
public String toString()
```

Gibt die Zeichenkettenrepräsentation des aktuellen Punktes zurück.

**Returns:**
Zeichenkette, die den aktuellen Punkt darstellt.
