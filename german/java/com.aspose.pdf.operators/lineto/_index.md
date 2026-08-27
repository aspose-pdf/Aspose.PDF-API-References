---
title: "LineTo"
linktitle: "LineTo"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den l-Operator (Linie zum Pfad hinzufügen) darstellt."
type: docs
weight: 380
url: /de/java/com.aspose.pdf.operators/lineto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.LineTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.LineTo

```
public class LineTo extends Operator
```

Klasse, die den l-Operator (Linie zum Pfad hinzufügen) darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [LineTo](#LineTo-double-double-) | Initialisiert den Linienoperator. |
| [LineTo](#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-) | Konstruktor für die Operator-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getX](#getX--) | X-Koordinate des Linienpunkts. |
| [getY](#getY--) | Y-Koordinate des Linienpunkts. |
| [setX](#setX-double-) | X-Koordinate des Linienpunkts. |
| [setY](#setY-double-) | Y-Koordinate des Linienpunkts. |
| [toString](#toString--) | Gibt die Textdarstellung des Operators zurück. |

### LineTo {#LineTo-double-double-}
```
public LineTo(double x, double y)
```

Initialisiert den Linienoperator.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x |  | X-Koordinate. |
| y |  | Y-Koordinate. |

### LineTo {#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-}
Konstruktor für die Operator-Klasse.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

### getX {#getX--}
```
public double getX()
```

X-Koordinate des Linienpunkts.

**Returns:**
double-Wert

### getY {#getY--}
```
public double getY()
```

Y-Koordinate des Linienpunkts.

**Returns:**
double-Wert

### setX {#setX-double-}
```
public void setX(double value)
```

X-Koordinate des Linienpunkts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setY {#setY-double-}
```
public void setY(double value)
```

Y-Koordinate des Linienpunkts.

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
