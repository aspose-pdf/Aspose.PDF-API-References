---
title: CurveTo1
second_title: Aspose.PDF for Java API Reference
description: Class representing v operator append curve to path initial point replicated.
type: docs
weight: 25
url: /java/com.aspose.pdf.operators/curveto1/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class CurveTo1 extends Operator
```

Class representing v operator (append curve to path, initial point replicated).
## Constructors

| Constructor | Description |
| --- | --- |
| [CurveTo1(double x2, double y2, double x3, double y3)](#CurveTo1-double-double-double-double-) | Initializes curve operator. |
## Methods

| Method | Description |
| --- | --- |
| [getPoints()](#getPoints--) | Points of the curve. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts operator selector. |
### CurveTo1(double x2, double y2, double x3, double y3) {#CurveTo1-double-double-double-double-}
```
public CurveTo1(double x2, double y2, double x3, double y3)
```


Initializes curve operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x2 | double | Abscissa of second point. |
| y2 | double | Ordinate of second point. |
| x3 | double | Abscissa of third point. |
| y3 | double | Ordinate of third point. |

### getPoints() {#getPoints--}
```
public Point[] getPoints()
```


Points of the curve.

**Returns:**
com.aspose.pdf.Point[] - array of Point instances
### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts operator selector.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object |

