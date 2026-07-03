---
title: CurveTo
linktitle: CurveTo
second_title: Aspose.PDF for Java API Reference
description: Class representing c operator (append curve to path).
type: docs
weight: 150
url: /java/com.aspose.pdf.operators/curveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo

```
public class CurveTo extends Operator
```

Class representing c operator (append curve to path).

## Fields

| Field | Description |
| --- | --- |
| [X1](#X1) | Gets or sets the X1 coordinate. |
| [X2](#X2) | Gets or sets the X2 coordinate. |
| [X3](#X3) | Gets or sets the X3 coordinate. |
| [Y1](#Y1) | Gets or sets the Y1 coordinate. |
| [Y2](#Y2) | Gets or sets the Y2 coordinate. |
| [Y3](#Y3) | Gets or sets the Y3 coordinate. |

## Constructors

| Constructor | Description |
| --- | --- |
| [CurveTo](#CurveTo-double-double-double-double-double-double-) | Initializes curve operator. |
| [CurveTo](#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-) | Constructor for operator class. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toCommand](#toCommand--) | For internal usage only! |
| [toString](#toString--) | Returns text representation of operator. |

### X1 {#X1}
```
public double X1
```

Gets or sets the X1 coordinate.

### X2 {#X2}
```
public double X2
```

Gets or sets the X2 coordinate.

### X3 {#X3}
```
public double X3
```

Gets or sets the X3 coordinate.

### Y1 {#Y1}
```
public double Y1
```

Gets or sets the Y1 coordinate.

### Y2 {#Y2}
```
public double Y2
```

Gets or sets the Y2 coordinate.

### Y3 {#Y3}
```
public double Y3
```

Gets or sets the Y3 coordinate.

### CurveTo {#CurveTo-double-double-double-double-double-double-}
```
public CurveTo(double x1, double y1, double x2, double y2, double x3, double y3)
```

Initializes curve operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 |  | Abscissa of first point. |
| y1 |  | Ordinate of first point. |
| x2 |  | Abscissa of second point. |
| y2 |  | Ordinate of second point. |
| x3 |  | Abscissa of third point. |
| y3 |  | Ordinate of third point. |

### CurveTo {#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-}
Constructor for operator class.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

For internal usage only!

**Returns:**
ICommand value ICommand object

### toString {#toString--}
```
public String toString()
```

Returns text representation of operator.

**Returns:**
Text representation of operator.
