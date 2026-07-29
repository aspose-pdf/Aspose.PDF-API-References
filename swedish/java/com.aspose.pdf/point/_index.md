---
title: "Punkt"
linktitle: "Punkt"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en punkt med bråkliga koordinater."
type: docs
weight: 3870
url: /sv/java/com.aspose.pdf/point/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Point

```
public final class Point extends Object
```

Representerar en punkt med bråkliga koordinater.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Point](#Point-double-double-) | Initierar en ny instans av {@code Point}. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [distance](#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Beräknar avståndet mellan två punkter. |
| [getTrivial](#getTrivial--) | Hämtar punkt med nollkoordinater. |
| [getX](#getX--) | Hämtar X-koordinatvärdet. |
| [getY](#getY--) | Hämtar Y-koordinatvärdet. |
| [setX](#setX-double-) | Ställer in X-koordinatvärdet. |
| [setY](#setY-double-) | Ställer in Y-koordinatvärdet. |
| [toPoint](#toPoint--) | Konverterar punkt till java.awt.geom.Point2D.Float-objekt. |
| [toString](#toString--) | Returnerar strängrepresentation av aktuell punkt. |

### Point {#Point-double-double-}
```
public Point(double x, double y)
```

Initierar en ny instans av {@code Point}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x |  | x-koordinatvärde. |
| y |  | y-koordinatvärde. |

### distance {#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Beräknar avståndet mellan två punkter.

### getTrivial {#getTrivial--}
```
public static Point getTrivial()
```

Hämtar punkt med nollkoordinater.

**Returns:**
Point objekt

### getX {#getX--}
```
public double getX()
```

Hämtar X-koordinatvärdet.

**Returns:**
double-värde

### getY {#getY--}
```
public double getY()
```

Hämtar Y-koordinatvärdet.

**Returns:**
double-värde

### setX {#setX-double-}
```
public void setX(double value)
```

Ställer in X-koordinatvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setY {#setY-double-}
```
public void setY(double value)
```

Ställer in Y-koordinatvärdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### toPoint {#toPoint--}
```
public Point2D.Float toPoint()
```

Konverterar punkt till java.awt.geom.Point2D.Float-objekt.

**Returns:**
Float-struktur.

### toString {#toString--}
```
public String toString()
```

Returnerar strängrepresentation av aktuell punkt.

**Returns:**
Sträng som representerar aktuell punkt.
