---
title: Operator.CurveTo
second_title: Aspose.PDF for Java API Reference
description: Class representing c operator append curve to path.
type: docs
weight: 22
url: /java/com.aspose.pdf/operator.curveto/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public static class Operator.CurveTo extends Operator
```

Class representing c operator (append curve to path).
## Constructors

| Constructor | Description |
| --- | --- |
| [CurveTo(double x1, double y1, double x2, double y2, double x3, double y3)](#CurveTo-double-double-double-double-double-double-) | Initizlizes curve operator. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operator. |
### CurveTo(double x1, double y1, double x2, double y2, double x3, double y3) {#CurveTo-double-double-double-double-double-double-}
```
public CurveTo(double x1, double y1, double x2, double y2, double x3, double y3)
```


Initizlizes curve operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | double | Abscissa of first point. |
| y1 | double | Ordinate of first point. |
| x2 | double | Abscissa of second point. |
| y2 | double | Ordinate of second point. |
| x3 | double | Abscissa of third point. |
| y3 | double | Ordinate of third point. |

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
