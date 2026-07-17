---
title: CurveTo1
linktitle: CurveTo1
second_title: Aspose.PDF for Java API Reference
description: Class representing v operator (append curve to path, initial point replicated).
type: docs
weight: 160
url: /java/com.aspose.pdf.operators/curveto1/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo1, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo1

```
public class CurveTo1 extends Operator
```

Class representing v operator (append curve to path, initial point replicated).

## Constructors

| Constructor | Description |
| --- | --- |
| [CurveTo1](#CurveTo1-double-double-double-double-) | Initializes curve operator. |
| [CurveTo1](#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-) | Constructor for operator class. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts operator selector. |
| [getPoints](#getPoints--) | Points of the curve. |

### CurveTo1 {#CurveTo1-double-double-double-double-}
```
public CurveTo1(double x2, double y2, double x3, double y3)
```

Initializes curve operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x2 |  | Abscissa of second point. |
| y2 |  | Ordinate of second point. |
| x3 |  | Abscissa of third point. |
| y3 |  | Ordinate of third point. |

### CurveTo1 {#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-}
Constructor for operator class.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts operator selector.

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Points of the curve.

**Returns:**
array of Point instances
