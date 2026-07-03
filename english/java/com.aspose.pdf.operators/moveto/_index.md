---
title: MoveTo
second_title: Aspose.PDF for Java API Reference
description: Class representing {@code operators.m} (move to and begin new subpath).
type: docs
weight: 410
url: /java/com.aspose.pdf.operators/moveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.MoveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.MoveTo

```
public class MoveTo extends Operator
```

Class representing {@code operators.m} (move to and begin new subpath).

## Constructors

| Constructor | Description |
| --- | --- |
| [MoveTo](#MoveTo-double-double-) | Inintalizes new {@code Operator.m} (move to) operator. |
| [MoveTo](#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-) |  |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getX](#getX--) | X coordinate |
| [getY](#getY--) | Y coordinate |
| [setX](#setX-double-) | X coordinate |
| [setY](#setY-double-) | Y coordinate |
| [toString](#toString--) | Returns text representation of the operator. |

### MoveTo {#MoveTo-double-double-}
```
public MoveTo(double x, double y)
```

Inintalizes new {@code Operator.m} (move to) operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x |  | The x-coordinate. |
| y |  | The y-coordinate. |

### MoveTo {#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

### getX {#getX--}
```
public double getX()
```

X coordinate

**Returns:**
double value

### getY {#getY--}
```
public double getY()
```

Y coordinate

**Returns:**
double value

### setX {#setX-double-}
```
public void setX(double value)
```

X coordinate

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setY {#setY-double-}
```
public void setY(double value)
```

Y coordinate

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
