---
title: MoveTo
second_title: Aspose.PDF for Java API Reference
description: Class representing operators.m move to and begin new subpath.
type: docs
weight: 48
url: /java/com.aspose.pdf.operators/moveto/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class MoveTo extends Operator
```

Class representing  operators.m  (move to and begin new subpath).
## Constructors

| Constructor | Description |
| --- | --- |
| [MoveTo(int index, ICommand command)](#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) |  |
| [MoveTo(double x, double y)](#MoveTo-double-double-) | Inintalizes new  Operator.m  (move to) operator. |
## Methods

| Method | Description |
| --- | --- |
| [getX()](#getX--) | X coordinate |
| [setX(double value)](#setX-double-) | X coordinate |
| [getY()](#getY--) | Y coordinate |
| [setY(double value)](#setY-double-) | Y coordinate |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of the operator. |
### MoveTo(int index, ICommand command) {#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public MoveTo(int index, ICommand command)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) |  |

### MoveTo(double x, double y) {#MoveTo-double-double-}
```
public MoveTo(double x, double y)
```


Inintalizes new  Operator.m  (move to) operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | double | The x-coordinate. |
| y | double | The y-coordinate. |

### getX() {#getX--}
```
public double getX()
```


X coordinate

**Returns:**
double - double value
### setX(double value) {#setX-double-}
```
public void setX(double value)
```


X coordinate

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getY() {#getY--}
```
public double getY()
```


Y coordinate

**Returns:**
double - double value
### setY(double value) {#setY-double-}
```
public void setY(double value)
```


Y coordinate

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
