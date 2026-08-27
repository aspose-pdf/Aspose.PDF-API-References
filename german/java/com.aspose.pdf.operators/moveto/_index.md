---
title: "MoveTo"
linktitle: "MoveTo"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die {@code operators.m} (zu einem Punkt bewegen und neuen Teilpfad beginnen) darstellt."
type: docs
weight: 410
url: /de/java/com.aspose.pdf.operators/moveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.MoveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.MoveTo

```
public class MoveTo extends Operator
```

Klasse, die {@code operators.m} (zu einem Punkt bewegen und neuen Teilpfad beginnen) darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MoveTo](#MoveTo-double-double-) | Initialisiert neuen {@code Operator.m} (move to) Operator. |
| [MoveTo](#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getX](#getX--) | X-Koordinate |
| [getY](#getY--) | Y-Koordinate |
| [setX](#setX-double-) | X-Koordinate |
| [setY](#setY-double-) | Y-Koordinate |
| [toString](#toString--) | Gibt die Textdarstellung des Operators zurück. |

### MoveTo {#MoveTo-double-double-}
```
public MoveTo(double x, double y)
```

Initialisiert neuen {@code Operator.m} (move to) Operator.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x |  | Die x-Koordinate. |
| y |  | Die y-Koordinate. |

### MoveTo {#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

### getX {#getX--}
```
public double getX()
```

X-Koordinate

**Returns:**
double-Wert

### getY {#getY--}
```
public double getY()
```

Y-Koordinate

**Returns:**
double-Wert

### setX {#setX-double-}
```
public void setX(double value)
```

X-Koordinate

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setY {#setY-double-}
```
public void setY(double value)
```

Y-Koordinate

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
