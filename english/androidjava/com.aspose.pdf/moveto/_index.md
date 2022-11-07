---
title: Operator.MoveTo
second_title: Aspose.PDF for Java API Reference
description: Class representing m operator move to and begin new subpath.
type: docs
weight: 45
url: /java/com.aspose.pdf/operator.moveto/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public static class Operator.MoveTo extends Operator
```

Class representing m operator (move to and begin new subpath).
## Constructors

| Constructor | Description |
| --- | --- |
| [MoveTo(double x, double y)](#MoveTo-double-double-) | Inintalizes new  Operator.m  (move to) operator. |
## Methods

| Method | Description |
| --- | --- |
| [getX()](#getX--) | X coordinate |
| [setX(double value)](#setX-double-) |  |
| [getY()](#getY--) | Y coordinate |
| [setY(double value)](#setY-double-) |  |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of the operator. |
### MoveTo(double x, double y) {#MoveTo-double-double-}
```
public MoveTo(double x, double y)
```


Inintalizes new  Operator.m  (move to) operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | double | x value. |
| y | double | y value. |

### getX() {#getX--}
```
public double getX()
```


X coordinate

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


Y coordinate

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


Returns text representation of the operator.

**Returns:**
java.lang.String - Text representation of the operator.
