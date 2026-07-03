---
title: MoveTextPosition
second_title: Aspose.PDF for Java API Reference
description: Class representing Td operator (move text position).
type: docs
weight: 390
url: /java/com.aspose.pdf.operators/movetextposition/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPosition, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.MoveTextPosition

```
public class MoveTextPosition extends TextPlaceOperator
```

Class representing Td operator (move text position).

## Constructors

| Constructor | Description |
| --- | --- |
| [MoveTextPosition](#MoveTextPosition-double-double-) | Initializes operator. |
| [MoveTextPosition](#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-) | Initializes operator. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getX](#getX--) | X coordinate of text position. |
| [getY](#getY--) | Y coordinate of text position. |
| [setX](#setX-double-) | X coordinate of text position. |
| [setY](#setY-double-) | Y coordinate of text position. |
| [toString](#toString--) | Returns text representation of operator. |

### MoveTextPosition {#MoveTextPosition-double-double-}
```
public MoveTextPosition(double x, double y)
```

Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x |  | X coordinate of text position. |
| y |  | Y coordinate of text position. |

### MoveTextPosition {#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLine-}
Initializes operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

### getX {#getX--}
```
public double getX()
```

X coordinate of text position.

**Returns:**
double value

### getY {#getY--}
```
public double getY()
```

Y coordinate of text position.

**Returns:**
double value

### setX {#setX-double-}
```
public void setX(double value)
```

X coordinate of text position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setY {#setY-double-}
```
public void setY(double value)
```

Y coordinate of text position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### toString {#toString--}
```
public String toString()
```

Returns text representation of operator.

**Returns:**
Text representation of operator.
