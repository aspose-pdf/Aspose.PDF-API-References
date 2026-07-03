---
title: Point
second_title: Aspose.PDF for Java API Reference
description: Represent point with fractional coordinates.
type: docs
weight: 3870
url: /java/com.aspose.pdf/point/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Point

```
public final class Point extends Object
```

Represent point with fractional coordinates.

## Constructors

| Constructor | Description |
| --- | --- |
| [Point](#Point-double-double-) | Initializes new instance of the {@code Point}. |

## Methods

| Method | Description |
| --- | --- |
| [distance](#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Calculates distance between two points. |
| [getTrivial](#getTrivial--) | Gets point with zero coordinates. |
| [getX](#getX--) | Gets X coordinate value. |
| [getY](#getY--) | Gets Y coordinate value. |
| [setX](#setX-double-) | Sets X coordinate value. |
| [setY](#setY-double-) | Sets Y coordinate value. |
| [toPoint](#toPoint--) | Converts point into java.awt.geom.Point2D.Float object. |
| [toString](#toString--) | Return string representation current point. |

### Point {#Point-double-double-}
```
public Point(double x, double y)
```

Initializes new instance of the {@code Point}.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x |  | x coordinate value. |
| y |  | y coordinate value. |

### distance {#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Calculates distance between two points.

### getTrivial {#getTrivial--}
```
public static Point getTrivial()
```

Gets point with zero coordinates.

**Returns:**
Point object

### getX {#getX--}
```
public double getX()
```

Gets X coordinate value.

**Returns:**
double value

### getY {#getY--}
```
public double getY()
```

Gets Y coordinate value.

**Returns:**
double value

### setX {#setX-double-}
```
public void setX(double value)
```

Sets X coordinate value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setY {#setY-double-}
```
public void setY(double value)
```

Sets Y coordinate value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### toPoint {#toPoint--}
```
public Point2D.Float toPoint()
```

Converts point into java.awt.geom.Point2D.Float object.

**Returns:**
Float structure.

### toString {#toString--}
```
public String toString()
```

Return string representation current point.

**Returns:**
String, representing current point.
