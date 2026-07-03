---
title: Re
linktitle: Re
second_title: Aspose.PDF for Java API Reference
description: Class representing re operator (add rectangle to the path).
type: docs
weight: 460
url: /java/com.aspose.pdf.operators/re/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Re, com.aspose.pdf.Operator, com.aspose.pdf.operators.Re

```
public class Re extends Operator
```

Class representing re operator (add rectangle to the path).

## Constructors

| Constructor | Description |
| --- | --- |
| [Re](#Re--) | Constructor for extracting goals. |
| [Re](#Re-double-double-double-double-) | Constructor for writing program. |
| [Re](#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-) | Constructor for extracting goals. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getHeight](#getHeight--) | Height of the rectangle. |
| [getWidth](#getWidth--) | Gets width of the rectangle. |
| [getX](#getX--) | X coordinate of most left side of rectangle. |
| [getY](#getY--) | Y coordinate of bottom side of rectangle. |
| [setHeight](#setHeight-double-) | Height of the rectangle. |
| [setWidth](#setWidth-double-) | Sets width of the rectangle. |
| [setX](#setX-double-) | X coordinate of most left side of rectangle. |
| [setY](#setY-double-) | Y coordinate of bottom side of rectangle. |
| [toString](#toString--) | Returns text representation of the operator. |

### Re {#Re--}
```
public Re()
```

Constructor for extracting goals.

### Re {#Re-double-double-double-double-}
```
public Re(double x, double y, double width, double height)
```

Constructor for writing program.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x |  | The x-coordinate of the bottom-left corner of the rectangle. |
| y |  | The y-coordinate of the bottom-left corner of the rectangle. |
| width |  | The width of the rectangle. |
| height |  | The height of the rectangle. |

### Re {#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-}
Constructor for extracting goals.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

### getHeight {#getHeight--}
```
public double getHeight()
```

Height of the rectangle.

**Returns:**
Height of the rectangle.

### getWidth {#getWidth--}
```
public double getWidth()
```

Gets width of the rectangle.

**Returns:**
width of the rectangle.

### getX {#getX--}
```
public double getX()
```

X coordinate of most left side of rectangle.

**Returns:**
double value

### getY {#getY--}
```
public double getY()
```

Y coordinate of bottom side of rectangle.

**Returns:**
double value

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Height of the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | Height of the rectangle. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Sets width of the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | width of the rectangle. |

### setX {#setX-double-}
```
public void setX(double value)
```

X coordinate of most left side of rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setY {#setY-double-}
```
public void setY(double value)
```

Y coordinate of bottom side of rectangle.

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
