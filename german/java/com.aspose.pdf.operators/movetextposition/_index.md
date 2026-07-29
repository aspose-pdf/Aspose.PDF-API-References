---
title: "MoveTextPosition"
linktitle: "MoveTextPosition"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den Td-Operator (Textposition verschieben) darstellt."
type: docs
weight: 390
url: /de/java/com.aspose.pdf.operators/movetextposition/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.MoveTextPosition

```
public class MoveTextPosition extends TextPlaceOperator
```

Klasse, die den Td-Operator (Textposition verschieben) darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MoveTextPosition](#MoveTextPosition-double-double-) | Initialisiert den Operator. |
| [MoveTextPosition](#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-) | Initialisiert den Operator. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getX](#getX--) | X-Koordinate der Textposition. |
| [getY](#getY--) | Y-Koordinate der Textposition. |
| [setX](#setX-double-) | X-Koordinate der Textposition. |
| [setY](#setY-double-) | Y-Koordinate der Textposition. |
| [toString](#toString--) | Gibt die Textdarstellung des Operators zurück. |

### MoveTextPosition {#MoveTextPosition-double-double-}
```
public MoveTextPosition(double x, double y)
```

Initialisiert den Operator.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x |  | X-Koordinate der Textposition. |
| y |  | Y-Koordinate der Textposition. |

### MoveTextPosition {#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-}
Initialisiert den Operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

### getX {#getX--}
```
public double getX()
```

X-Koordinate der Textposition.

**Returns:**
double-Wert

### getY {#getY--}
```
public double getY()
```

Y-Koordinate der Textposition.

**Returns:**
double-Wert

### setX {#setX-double-}
```
public void setX(double value)
```

X-Koordinate der Textposition.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setY {#setY-double-}
```
public void setY(double value)
```

Y-Koordinate der Textposition.

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
