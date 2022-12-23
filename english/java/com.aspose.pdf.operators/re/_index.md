---
title: Re
second_title: Aspose.PDF for Java API Reference
description: Class representing re operator add rectangle to the path.
type: docs
weight: 52
url: /java/com.aspose.pdf.operators/re/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class Re extends Operator
```

Class representing re operator (add rectangle to the path).
## Constructors

| Constructor | Description |
| --- | --- |
| [Re(int index, ICommand command)](#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [Re()](#Re--) | Constructor for extracting goals. |
| [Re(double x, double y, double width, double height)](#Re-double-double-double-double-) | Constructor for writing program. |
## Methods

| Method | Description |
| --- | --- |
| [getX()](#getX--) | X coordinate of most left side of rectangle. |
| [setX(double value)](#setX-double-) | X coordinate of most left side of rectangle. |
| [getY()](#getY--) | Y coordinate of bottom side of rectangle. |
| [setY(double value)](#setY-double-) | Y coordinate of bottom side of rectangle. |
| [getWidth()](#getWidth--) | Gets width of the rectangle. |
| [setWidth(double value)](#setWidth-double-) | Sets width of the rectangle. |
| [getHeight()](#getHeight--) | Height of the rectangle. |
| [setHeight(double value)](#setHeight-double-) | Height of the rectangle. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of the operator. |
### Re(int index, ICommand command) {#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public Re(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### Re() {#Re--}
```
public Re()
```


Constructor for extracting goals.

### Re(double x, double y, double width, double height) {#Re-double-double-double-double-}
```
public Re(double x, double y, double width, double height)
```


Constructor for writing program.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | double | The x-coordinate of the bottom-left corner of the rectangle. |
| y | double | The y-coordinate of the bottom-left corner of the rectangle. |
| width | double | The width of the rectangle. |
| height | double | The height of the rectangle. |

### getX() {#getX--}
```
public double getX()
```


X coordinate of most left side of rectangle.

**Returns:**
double - double value
### setX(double value) {#setX-double-}
```
public void setX(double value)
```


X coordinate of most left side of rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getY() {#getY--}
```
public double getY()
```


Y coordinate of bottom side of rectangle.

**Returns:**
double - double value
### setY(double value) {#setY-double-}
```
public void setY(double value)
```


Y coordinate of bottom side of rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets width of the rectangle.

**Returns:**
double - width of the rectangle.
### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Sets width of the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | width of the rectangle. |

### getHeight() {#getHeight--}
```
public double getHeight()
```


Height of the rectangle.

**Returns:**
double - Height of the rectangle.
### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Height of the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Height of the rectangle. |

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
