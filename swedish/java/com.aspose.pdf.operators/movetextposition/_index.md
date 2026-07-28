---
title: "MoveTextPosition"
linktitle: "MoveTextPosition"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar Td operator (flytta textposition)."
type: docs
weight: 390
url: /sv/java/com.aspose.pdf.operators/movetextposition/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.MoveTextPosition

```
public class MoveTextPosition extends TextPlaceOperator
```

Klass som representerar Td operator (flytta textposition).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [MoveTextPosition](#MoveTextPosition-double-double-) | Initierar operatorn. |
| [MoveTextPosition](#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-) | Initierar operatorn. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getX](#getX--) | X-koordinat för textposition. |
| [getY](#getY--) | Y-koordinat för textposition. |
| [setX](#setX-double-) | X-koordinat för textposition. |
| [setY](#setY-double-) | Y-koordinat för textposition. |
| [toString](#toString--) | Returnerar textrepresentation av operatorn. |

### MoveTextPosition {#MoveTextPosition-double-double-}
```
public MoveTextPosition(double x, double y)
```

Initierar operatorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x |  | X-koordinat för textposition. |
| y |  | Y-koordinat för textposition. |

### MoveTextPosition {#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-}
Initierar operatorn.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökarobjekt för att bearbeta operatorn.

### getX {#getX--}
```
public double getX()
```

X-koordinat för textposition.

**Returns:**
double-värde

### getY {#getY--}
```
public double getY()
```

Y-koordinat för textposition.

**Returns:**
double-värde

### setX {#setX-double-}
```
public void setX(double value)
```

X-koordinat för textposition.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setY {#setY-double-}
```
public void setY(double value)
```

Y-koordinat för textposition.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### toString {#toString--}
```
public String toString()
```

Returnerar textrepresentation av operatorn.

**Returns:**
Textrepresentation av operator.
