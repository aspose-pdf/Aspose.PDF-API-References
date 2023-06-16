---
title: LineTo
second_title: Aspose.PDF for Java API Reference
description: Class representing l operator add line to the path.
type: docs
weight: 46
url: /java/com.aspose.pdf.operators/lineto/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class LineTo extends Operator
```

Class representing l operator (add line to the path).
## Constructors

| Constructor | Description |
| --- | --- |
| [LineTo(int index, ICommand command)](#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [LineTo(double x, double y)](#LineTo-double-double-) | Initializes line operator. |
## Methods

| Method | Description |
| --- | --- |
| [getX()](#getX--) | X coordinate of line point. |
| [setX(double value)](#setX-double-) | X coordinate of line point. |
| [getY()](#getY--) | Y coordinate of line point. |
| [setY(double value)](#setY-double-) | Y coordinate of line point. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of the operator. |
### LineTo(int index, ICommand command) {#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public LineTo(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### LineTo(double x, double y) {#LineTo-double-double-}
```
public LineTo(double x, double y)
```


Initializes line operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | double | X coordinate. |
| y | double | Y coordinate. |

### getX() {#getX--}
```
public double getX()
```


X coordinate of line point.

**Returns:**
double - double value
### setX(double value) {#setX-double-}
```
public void setX(double value)
```


X coordinate of line point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getY() {#getY--}
```
public double getY()
```


Y coordinate of line point.

**Returns:**
double - double value
### setY(double value) {#setY-double-}
```
public void setY(double value)
```


Y coordinate of line point.

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


Returns text representation of the operator.

**Returns:**
java.lang.String - Text representation of the operator.
