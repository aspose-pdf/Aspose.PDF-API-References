---
title: Operator.LineTo
second_title: Aspose.PDF for Java API Reference
description: Class representing l operator add line to the path.
type: docs
weight: 41
url: /java/com.aspose.pdf/operator.lineto/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public static class Operator.LineTo extends Operator
```

Class representing l operator (add line to the path).
## Constructors

| Constructor | Description |
| --- | --- |
| [LineTo(double x, double y)](#LineTo-double-double-) | Initializes line operator. |
## Methods

| Method | Description |
| --- | --- |
| [getX()](#getX--) | X coordinate of line point. |
| [setX(double value)](#setX-double-) |  |
| [getY()](#getY--) | Y coordinate of line point. |
| [setY(double value)](#setY-double-) |  |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of the operator. |
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


Y coordinate of line point.

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
java.lang.String - 
