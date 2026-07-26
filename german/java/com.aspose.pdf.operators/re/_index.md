---
title: "Re"
linktitle: "Re"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den re-Operator darstellt (Rechteck zum Pfad hinzufügen)."
type: docs
weight: 460
url: /de/java/com.aspose.pdf.operators/re/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Re, com.aspose.pdf.Operator, com.aspose.pdf.operators.Re

```
public class Re extends Operator
```

Klasse, die den re-Operator darstellt (Rechteck zum Pfad hinzufügen).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Re](#Re--) | Konstruktor zum Extrahieren von Zielen. |
| [Re](#Re-double-double-double-double-) | Konstruktor für das Schreibprogramm. |
| [Re](#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-) | Konstruktor zum Extrahieren von Zielen. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getHeight](#getHeight--) | Höhe des Rechtecks. |
| [getWidth](#getWidth--) | Gibt die Breite des Rechtecks zurück. |
| [getX](#getX--) | X-Koordinate der linken Seite des Rechtecks. |
| [getY](#getY--) | Y-Koordinate der Unterseite des Rechtecks. |
| [setHeight](#setHeight-double-) | Höhe des Rechtecks. |
| [setWidth](#setWidth-double-) | Setzt die Breite des Rechtecks. |
| [setX](#setX-double-) | X-Koordinate der linken Seite des Rechtecks. |
| [setY](#setY-double-) | Y-Koordinate der Unterseite des Rechtecks. |
| [toString](#toString--) | Gibt die Textdarstellung des Operators zurück. |

### Re {#Re--}
```
public Re()
```

Konstruktor zum Extrahieren von Zielen.

### Re {#Re-double-double-double-double-}
```
public Re(double x, double y, double width, double height)
```

Konstruktor für das Schreibprogramm.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x |  | Die X-Koordinate der unteren linken Ecke des Rechtecks. |
| y |  | Die Y-Koordinate der unteren linken Ecke des Rechtecks. |
| Breite |  | Die Breite des Rechtecks. |
| Höhe |  | Die Höhe des Rechtecks. |

### Re {#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-}
Konstruktor zum Extrahieren von Zielen.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

### getHeight {#getHeight--}
```
public double getHeight()
```

Höhe des Rechtecks.

**Returns:**
Höhe des Rechtecks.

### getWidth {#getWidth--}
```
public double getWidth()
```

Gibt die Breite des Rechtecks zurück.

**Returns:**
Breite des Rechtecks.

### getX {#getX--}
```
public double getX()
```

X-Koordinate der linken Seite des Rechtecks.

**Returns:**
double-Wert

### getY {#getY--}
```
public double getY()
```

Y-Koordinate der Unterseite des Rechtecks.

**Returns:**
double-Wert

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Höhe des Rechtecks.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Höhe des Rechtecks. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Setzt die Breite des Rechtecks.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Breite des Rechtecks. |

### setX {#setX-double-}
```
public void setX(double value)
```

X-Koordinate der linken Seite des Rechtecks.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setY {#setY-double-}
```
public void setY(double value)
```

Y-Koordinate der Unterseite des Rechtecks.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### toString {#toString--}
```
public String toString()
```

Gibt die Textdarstellung des Operators zurück.

**Returns:**
Textdarstellung des Operators.
