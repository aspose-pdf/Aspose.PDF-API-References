---
title: "MoveTextPositionSetLeading"
linktitle: "MoveTextPositionSetLeading"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den TD-Operator (Position verschieben und Zeilenabstand setzen) darstellt."
type: docs
weight: 400
url: /de/java/com.aspose.pdf.operators/movetextpositionsetleading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPositionSetLeading, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPositionSetLeading, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPositionSetLeading, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.MoveTextPositionSetLeading

```
public class MoveTextPositionSetLeading extends TextPlaceOperator
```

Klasse, die den TD-Operator (Position verschieben und Zeilenabstand setzen) darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MoveTextPositionSetLeading](#MoveTextPositionSetLeading-double-double-) | Initialisiert den Operator. |
| [MoveTextPositionSetLeading](#MoveTextPositionSetLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLineAndSetLeading-) | Konstruktor für die Operator-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getX](#getX--) | X-Koordinate der Textposition. |
| [getY](#getY--) | Y-Koordinate der Textposition. |
| [setX](#setX-double-) | X-Koordinate der Textposition. |
| [setY](#setY-double-) | Y-Koordinate der Textposition. |

### MoveTextPositionSetLeading {#MoveTextPositionSetLeading-double-double-}
```
public MoveTextPositionSetLeading(double x, double y)
```

Initialisiert den Operator.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x |  | X-Koordinate der Textposition. |
| y |  | Y-Koordinate der Textposition. |

### MoveTextPositionSetLeading {#MoveTextPositionSetLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLineAndSetLeading-}
Konstruktor für die Operator-Klasse.

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
