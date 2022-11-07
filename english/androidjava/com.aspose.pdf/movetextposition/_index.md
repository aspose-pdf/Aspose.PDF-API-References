---
title: Operator.MoveTextPosition
second_title: Aspose.PDF for Java API Reference
description: Class representing Td operator move text position.
type: docs
weight: 43
url: /java/com.aspose.pdf/operator.movetextposition/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.Operator.TextOperator](../../com.aspose.pdf/textoperator), [com.aspose.pdf.Operator.TextPlaceOperator](../../com.aspose.pdf/textplaceoperator)
```
public static class Operator.MoveTextPosition extends Operator.TextPlaceOperator
```

Class representing Td operator (move text position).
## Constructors

| Constructor | Description |
| --- | --- |
| [MoveTextPosition(double x, double y)](#MoveTextPosition-double-double-) | Constructor for writing program. |
## Methods

| Method | Description |
| --- | --- |
| [getX()](#getX--) | X coordinate of text position. |
| [setX(double value)](#setX-double-) |  |
| [getY()](#getY--) | Y coordinate of text position. |
| [setY(double value)](#setY-double-) |  |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operator. |
### MoveTextPosition(double x, double y) {#MoveTextPosition-double-double-}
```
public MoveTextPosition(double x, double y)
```


Constructor for writing program.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | double |  |
| y | double |  |

### getX() {#getX--}
```
public double getX()
```


X coordinate of text position.

**Returns:**
double
### setX(double value) {#setX-double-}
```
public void setX(double value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getY() {#getY--}
```
public double getY()
```


Y coordinate of text position.

**Returns:**
double
### setY(double value) {#setY-double-}
```
public void setY(double value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

### toString() {#toString--}
```
public String toString()
```


Returns text representation of operator.

**Returns:**
java.lang.String - Text representation of operator.
