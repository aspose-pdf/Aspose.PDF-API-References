---
title: Point
second_title: Aspose.PDF for Java API Reference
description: Represent point with fractional coordinates.
type: docs
weight: 230
url: /java/com.aspose.pdf/point/
---
**Inheritance:**
java.lang.Object
```
public final class Point
```

Represent point with fractional coordinates.
## Constructors

| Constructor | Description |
| --- | --- |
| [Point(double x, double y)](#Point-double-double-) | Initializes new instance of the  Point . |
## Methods

| Method | Description |
| --- | --- |
| [getX()](#getX--) | X value. |
| [setX(double value)](#setX-double-) |  |
| [getY()](#getY--) | Y value. |
| [setY(double value)](#setY-double-) |  |
| [getTrivial()](#getTrivial--) | Gets point with zero coordinates. |
| [toPoint()](#toPoint--) | Converts point into System.Drawing.PointF object. |
### Point(double x, double y) {#Point-double-double-}
```
public Point(double x, double y)
```


Initializes new instance of the  Point .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | double | x value. |
| y | double | y value. |

### getX() {#getX--}
```
public double getX()
```


X value.

**Returns:**
double
### setX(double value) {#setX-double-}
```
public void setX(double value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getY() {#getY--}
```
public double getY()
```


Y value.

**Returns:**
double
### setY(double value) {#setY-double-}
```
public void setY(double value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getTrivial() {#getTrivial--}
```
public static Point getTrivial()
```


Gets point with zero coordinates.

**Returns:**
[Point](../../com.aspose.pdf/point)
### toPoint() {#toPoint--}
```
public Point2D.Float toPoint()
```


Converts point into System.Drawing.PointF object.

**Returns:**
[Float](../../com.aspose.pdf.java.awt.geom.point2d/float)
