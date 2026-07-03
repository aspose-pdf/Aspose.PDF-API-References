---
title: CurveTo2
second_title: Aspose.PDF for Java API Reference
description: Class representing y operator (append curve to path, final point replicated).
type: docs
weight: 170
url: /java/com.aspose.pdf.operators/curveto2/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo2, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo2

```
public class CurveTo2 extends Operator
```

Class representing y operator (append curve to path, final point replicated).

## Constructors

| Constructor | Description |
| --- | --- |
| [CurveTo2](#CurveTo2-double-double-double-double-) | Initializes curve operator. |
| [CurveTo2](#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-) | Constructor for operator class. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getPoints](#getPoints--) | Points of the curve. |

### CurveTo2 {#CurveTo2-double-double-double-double-}
```
public CurveTo2(double x1, double y1, double x3, double y3)
```

Initializes curve operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 |  | Abscissa of second point. |
| y1 |  | Ordinate of second point. |
| x3 |  | Abscissa of third point. |
| y3 |  | Ordinate of third point. |

### CurveTo2 {#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-}
Constructor for operator class.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Points of the curve.

**Returns:**
array of Point instances
