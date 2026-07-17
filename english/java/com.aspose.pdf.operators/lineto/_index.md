---
title: LineTo
linktitle: LineTo
second_title: Aspose.PDF for Java API Reference
description: Class representing l operator (add line to the path).
type: docs
weight: 380
url: /java/com.aspose.pdf.operators/lineto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.LineTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.LineTo

```
public class LineTo extends Operator
```

Class representing l operator (add line to the path).

## Constructors

| Constructor | Description |
| --- | --- |
| [LineTo](#LineTo-double-double-) | Initializes line operator. |
| [LineTo](#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-) | Constructor for operator class. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getX](#getX--) | X coordinate of line point. |
| [getY](#getY--) | Y coordinate of line point. |
| [setX](#setX-double-) | X coordinate of line point. |
| [setY](#setY-double-) | Y coordinate of line point. |
| [toString](#toString--) | Returns text representation of the operator. |

### LineTo {#LineTo-double-double-}
```
public LineTo(double x, double y)
```

Initializes line operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x |  | X coordinate. |
| y |  | Y coordinate. |

### LineTo {#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-}
Constructor for operator class.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

### getX {#getX--}
```
public double getX()
```

X coordinate of line point.

**Returns:**
double value

### getY {#getY--}
```
public double getY()
```

Y coordinate of line point.

**Returns:**
double value

### setX {#setX-double-}
```
public void setX(double value)
```

X coordinate of line point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setY {#setY-double-}
```
public void setY(double value)
```

Y coordinate of line point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### toString {#toString--}
```
public String toString()
```

Returns text representation of the operator.

**Returns:**
Text representation of the operator.
