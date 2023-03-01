---
title: SetLineWidth
second_title: Aspose.PDF for Java API Reference
description: Class representing w operator set line width.
type: docs
weight: 75
url: /java/com.aspose.pdf.operators/setlinewidth/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class SetLineWidth extends Operator
```

Class representing w operator (set line width).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetLineWidth(double width)](#SetLineWidth-double-) | Initializes operator with width value. |
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Gets width of the line. |
| [setWidth(double value)](#setWidth-double-) | Sets width of the line. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operator. |
### SetLineWidth(double width) {#SetLineWidth-double-}
```
public SetLineWidth(double width)
```


Initializes operator with width value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | double | Value of width. |

### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets width of the line.

**Returns:**
double - width of the line.
### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Sets width of the line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | width of the line. |

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
