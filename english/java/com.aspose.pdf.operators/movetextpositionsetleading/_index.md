---
title: MoveTextPositionSetLeading
second_title: Aspose.PDF for Java API Reference
description: Class representing TD operator (move position and set leading).
type: docs
weight: 400
url: /java/com.aspose.pdf.operators/movetextpositionsetleading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPositionSetLeading, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPositionSetLeading, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextPlaceOperator com.aspose.pdf.operators.MoveTextPositionSetLeading, com.aspose.pdf.operators.TextPlaceOperator, com.aspose.pdf.operators.MoveTextPositionSetLeading

```
public class MoveTextPositionSetLeading extends TextPlaceOperator
```

Class representing TD operator (move position and set leading).

## Constructors

| Constructor | Description |
| --- | --- |
| [MoveTextPositionSetLeading](#MoveTextPositionSetLeading-double-double-) | Initializes operator. |
| [MoveTextPositionSetLeading](#MoveTextPositionSetLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLineAndSetLeading-) | Constructor for operator class. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getX](#getX--) | X coordinate of text position. |
| [getY](#getY--) | Y coordinate of text position. |
| [setX](#setX-double-) | X coordinate of text position. |
| [setY](#setY-double-) | Y coordinate of text position. |

### MoveTextPositionSetLeading {#MoveTextPositionSetLeading-double-double-}
```
public MoveTextPositionSetLeading(double x, double y)
```

Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x |  | X coordinate of text position. |
| y |  | Y coordinate of text position. |

### MoveTextPositionSetLeading {#MoveTextPositionSetLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textpositioningoperators.MoveToNextLineAndSetLeading-}
Constructor for operator class.

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
