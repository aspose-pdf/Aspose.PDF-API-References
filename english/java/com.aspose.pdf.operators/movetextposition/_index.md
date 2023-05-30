---
title: MoveTextPosition
second_title: Aspose.PDF for Java API Reference
description: Class representing Td operator move text position.
type: docs
weight: 48
url: /java/com.aspose.pdf.operators/movetextposition/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.TextOperator](../../com.aspose.pdf.operators/textoperator), [com.aspose.pdf.operators.TextPlaceOperator](../../com.aspose.pdf.operators/textplaceoperator)
```
public class MoveTextPosition extends TextPlaceOperator
```

Class representing Td operator (move text position).
## Constructors

| Constructor | Description |
| --- | --- |
| [MoveTextPosition(int index, ICommand command)](#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Initializes operator. |
| [MoveTextPosition(double x, double y)](#MoveTextPosition-double-double-) | Initializes operator. |
## Methods

| Method | Description |
| --- | --- |
| [getX()](#getX--) | X coordinate of text position. |
| [setX(double value)](#setX-double-) | X coordinate of text position. |
| [getY()](#getY--) | Y coordinate of text position. |
| [setY(double value)](#setY-double-) | Y coordinate of text position. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operator. |
### MoveTextPosition(int index, ICommand command) {#MoveTextPosition-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public MoveTextPosition(int index, ICommand command)
```


Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### MoveTextPosition(double x, double y) {#MoveTextPosition-double-double-}
```
public MoveTextPosition(double x, double y)
```


Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | double | X coordinate of text position. |
| y | double | Y coordinate of text position. |

### getX() {#getX--}
```
public double getX()
```


X coordinate of text position.

**Returns:**
double - double value
### setX(double value) {#setX-double-}
```
public void setX(double value)
```


X coordinate of text position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getY() {#getY--}
```
public double getY()
```


Y coordinate of text position.

**Returns:**
double - double value
### setY(double value) {#setY-double-}
```
public void setY(double value)
```


Y coordinate of text position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

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
