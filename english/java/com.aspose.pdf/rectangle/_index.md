---
title: Rectangle
linktitle: Rectangle
second_title: Aspose.PDF for Java API Reference
description: Class represents rectangle.
type: docs
weight: 4100
url: /java/com.aspose.pdf/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Rectangle

**All Implemented Interfaces:**
Cloneable, Comparable < Object >

```
public final class Rectangle extends Object implements Comparable < Object >, Cloneable
```

Class represents rectangle.

## Constructors

| Constructor | Description |
| --- | --- |
| [Rectangle](#Rectangle-double-double-double-double-) | Constructor of Rectangle. |
| [Rectangle](#Rectangle-double-double-double-double-boolean-) | Constructor of Rectangle. |

## Methods

| Method | Description |
| --- | --- |
| [_Intersect](#Z:Z_Intersect-com.aspose.pdf.Rectangle-) | Intersects rectangles. Obsolete method. Please use Intersect instead. |
| [center](#center--) | Returncs coordinates of center of the rectangle. |
| [clone](#clone--) | Clones the Rectangle object. |
| [compareTo](#compareTo-java.lang.Object-) | CompareTo |
| [contains](#contains-com.aspose.pdf.Point-) | Determinces whether given point is inside of the rectangle. |
| [contains](#contains-com.aspose.pdf.Point-boolean-) | Determinces whether given point is inside of the rectangle. |
| [containsLine](#containsLine-double-double-double-double-) | Determines whether the rectangle contains a line represented by two points. |
| [containsPoint](#containsPoint-double-double-) | Determines whether the given point is contained within the rectangle. |
| [deepClone](#deepClone--) | Clones the Rectangle object. |
| [equals](#equals-java.lang.Object-) | Check if rectangles are equal i.e. have same position and sizes. |
| [fromRect](#fromRect-java.awt.Rectangle-) | Initializes new rectangle from given instance of System.Drawing.Rectangle. |
| [fromRect](#fromRect-java.awt.geom.Rectangle2D.Float-) | Initializes new rectangle from given instance of System.Drawing.Rectangle. |
| [fromRectInternal](#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [getArea](#getArea--) | Calculates the area of the rectangle. |
| [getEmpty](#getEmpty--) | Gets empty rectangle |
| [getHeight](#getHeight--) | Get height of rectangle. |
| [getLLX](#getLLX--) | Gets X-coordinate of lower - left corner. |
| [getLLY](#getLLY--) | Gets Y - coordinate of lower-left corner. |
| [getTrivial](#getTrivial--) | Initializes trivial rectangle i.e. rectangle with zero position and size. |
| [getURX](#getURX--) | Gets X - coordinate of upper-right corner. |
| [getURY](#getURY--) | Gets Y - coordinate of upper-right corner. |
| [getWidth](#getWidth--) | Gets width of rectangle. |
| [hashCode](#hashCode--) | Returns a hash code value for the object. This method is supported for the benefit of hash tables such as those provided by {@link java.util.HashMap}. <p> The general contract of {@code hashCode} is: <ul> <li>Whenever it is invoked on the same object more than once during an execution of a Java application, the {@code hashCode} method must consistently return the same integer, provided no information used in {@code equals} comparisons on the object is modified. This integer need not remain consistent from one execution of an application to another execution of the same application. <li>If two objects are equal according to the {@code equals(Object)} method, then calling the {@code hashCode} method on each of the two objects must produce the same integer result. <li>It is <em>not</em> required that if two objects are unequal according to the {@link java.lang.Object#equals(java.lang.Object)} method, then calling the {@code hashCode} method on each of the two objects must produce distinct integer results. However, the programmer should be aware that producing distinct integer results for unequal objects may improve the performance of hash tables. </ul> <p> As much as is reasonably practical, the hashCode method defined by class {@code Object} does return distinct integers for distinct objects. (This is typically implemented by converting the internal address of the object into an integer, but this implementation technique is not required by the Java<span style="font-size:70%"><sup>TM</sup></span> programming language.) |
| [intersect](#intersect-com.aspose.pdf.Rectangle-) | Intersects to rectangles. |
| [isEmpty](#isEmpty--) | Checks if rectangle is empty. |
| [isInclude](#isInclude-com.aspose.pdf.Rectangle-double-) | Checks that this rectangle includes whole another rectangle. I.e. whole another rectangle is inside this rectangle. Difference with IsIntersect method is that IsIntersect will true for partly intersected rectangles but IsInclude will false. |
| [isIntersect](#isIntersect-com.aspose.pdf.Rectangle-) | Determines whether this rectangle intersects with other rectangle. |
| [isPoint](#isPoint--) | Checks if rectangle is point i.e. LLX is equal URX and LLY is equal URY. |
| [isTrivial](#isTrivial--) | Checks if rectangle is trivial i.e. has zero size and position. |
| [join](#join-com.aspose.pdf.Rectangle-) | Joins rectangles. |
| [moveBy](#moveBy-double-double-) | Shift rectangle by the specified deltas. |
| [nearEquals](#nearEquals-com.aspose.pdf.Rectangle-double-) | Check if rectangles are near equal i.e. have near same (up to delta) position and sizes. |
| [parse](#parse-java.lang.String-) | Try to parse string and extract from it rectangle components llx, lly, urx, ury. |
| [rotate](#rotate-com.aspose.pdf.Rotation-) | Rotate rectangle by the specified angle. |
| [rotateAngle](#rotateAngle-int-) | Rotate rectangle by the specified angle. |
| [setLLX](#setLLX-double-) | Sets X-coordinate of lower - left corner. |
| [setLLY](#setLLY-double-) | Sets Y - coordinate of lower-left corner. |
| [setURX](#setURX-double-) | Sets X - coordinate of upper-right corner. |
| [setURY](#setURY-double-) | Sets Y - coordinate of upper-right corner. |
| [toArray](#toArray-com.aspose.pdf.engine.data.ITrailerable-) |  |
| [toPoints](#toPoints--) | Converts rectangle into array of points ("QuadPoints"). |
| [toRect](#toRect--) | Converts rectangle to instance of System.Drawing.Rectangle. Floating-point positions and size are truncated. |
| [toString](#toString--) | Gets rectangle string representation. |

### Rectangle {#Rectangle-double-double-double-double-}
```
public Rectangle(double llx, double lly, double urx, double ury)
```

Constructor of Rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| llx |  | X of lower left corner. |
| lly |  | Y of lower left corner. |
| urx |  | X of upper right corner. |
| ury |  | Y of upper right corner. |

### Rectangle {#Rectangle-double-double-double-double-boolean-}
```
public Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates)
```

Constructor of Rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| llx |  | X of lower left corner. |
| lly |  | Y of lower left corner. |
| urx |  | X of upper right corner. |
| ury |  | Y of upper right corner. |
| normalizeCoordinates |  | Normalize coordinates of rectangle. |

### _Intersect {#Z:Z_Intersect-com.aspose.pdf.Rectangle-}
Intersects rectangles. Obsolete method. Please use Intersect instead.

### center {#center--}
```
public Point center()
```

Returncs coordinates of center of the rectangle.

**Returns:**
Point which is center of the rectangle.

### clone {#clone--}
```
public Rectangle clone()
```

Clones the Rectangle object.

**Returns:**
Clone object.

### compareTo {#compareTo-java.lang.Object-}
CompareTo

### contains {#contains-com.aspose.pdf.Point-}
Determinces whether given point is inside of the rectangle.

### contains {#contains-com.aspose.pdf.Point-boolean-}
Determinces whether given point is inside of the rectangle.

### containsLine {#containsLine-double-double-double-double-}
```
public final boolean containsLine(double x1, double y1, double x2, double y2)
```

Determines whether the rectangle contains a line represented by two points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 |  | The X coordinate of the start point of the line. |
| y1 |  | The Y coordinate of the start point of the line. |
| x2 |  | The X coordinate of the end point of the line. |
| y2 |  | The Y coordinate of the end point of the line. |

**Returns:**
{@code true} if the rectangle contains the line; otherwise, {@code false}.

### containsPoint {#containsPoint-double-double-}
```
public final boolean containsPoint(double x, double y)
```

Determines whether the given point is contained within the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x |  | X-coordinate of the point. |
| y |  | Y-coordinate of the point. |

**Returns:**
{@code true} if the point is contained within the rectangle; otherwise, {@code false}.

### deepClone {#deepClone--}
```
public Rectangle deepClone()
```

Clones the Rectangle object.

**Returns:**
Clone object.

### equals {#equals-java.lang.Object-}
Check if rectangles are equal i.e. have same position and sizes.

### fromRect {#fromRect-java.awt.Rectangle-}
Initializes new rectangle from given instance of System.Drawing.Rectangle.

### fromRect {#fromRect-java.awt.geom.Rectangle2D.Float-}
Initializes new rectangle from given instance of System.Drawing.Rectangle.

### fromRectInternal {#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-}


### getArea {#getArea--}
```
public final double getArea()
```

Calculates the area of the rectangle.

**Returns:**
The area of the rectangle as a double, calculated by multiplying the width and height.

### getEmpty {#getEmpty--}
```
public static Rectangle getEmpty()
```

Gets empty rectangle

**Returns:**
new Rectangle object

### getHeight {#getHeight--}
```
public double getHeight()
```

Get height of rectangle.

**Returns:**
double value

### getLLX {#getLLX--}
```
public double getLLX()
```

Gets X-coordinate of lower - left corner.

**Returns:**
double value

### getLLY {#getLLY--}
```
public double getLLY()
```

Gets Y - coordinate of lower-left corner.

**Returns:**
double value

### getTrivial {#getTrivial--}
```
public static Rectangle getTrivial()
```

Initializes trivial rectangle i.e. rectangle with zero position and size.

**Returns:**
new Rectangle object

### getURX {#getURX--}
```
public double getURX()
```

Gets X - coordinate of upper-right corner.

**Returns:**
double value

### getURY {#getURY--}
```
public double getURY()
```

Gets Y - coordinate of upper-right corner.

**Returns:**
double value

### getWidth {#getWidth--}
```
public double getWidth()
```

Gets width of rectangle.

**Returns:**
double value

### hashCode {#hashCode--}
```
public int hashCode()
```

Returns a hash code value for the object. This method is supported for the benefit of hash tables such as those provided by {@link java.util.HashMap}. <p> The general contract of {@code hashCode} is: <ul> <li>Whenever it is invoked on the same object more than once during an execution of a Java application, the {@code hashCode} method must consistently return the same integer, provided no information used in {@code equals} comparisons on the object is modified. This integer need not remain consistent from one execution of an application to another execution of the same application. <li>If two objects are equal according to the {@code equals(Object)} method, then calling the {@code hashCode} method on each of the two objects must produce the same integer result. <li>It is <em>not</em> required that if two objects are unequal according to the {@link java.lang.Object#equals(java.lang.Object)} method, then calling the {@code hashCode} method on each of the two objects must produce distinct integer results. However, the programmer should be aware that producing distinct integer results for unequal objects may improve the performance of hash tables. </ul> <p> As much as is reasonably practical, the hashCode method defined by class {@code Object} does return distinct integers for distinct objects. (This is typically implemented by converting the internal address of the object into an integer, but this implementation technique is not required by the Java<span style="font-size:70%"><sup>TM</sup></span> programming language.)

**Returns:**
a hash code value for this object. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### intersect {#intersect-com.aspose.pdf.Rectangle-}
Intersects to rectangles.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Checks if rectangle is empty.

**Returns:**
boolean value

### isInclude {#isInclude-com.aspose.pdf.Rectangle-double-}
Checks that this rectangle includes whole another rectangle. I.e. whole another rectangle is inside this rectangle. Difference with IsIntersect method is that IsIntersect will true for partly intersected rectangles but IsInclude will false.

### isIntersect {#isIntersect-com.aspose.pdf.Rectangle-}
Determines whether this rectangle intersects with other rectangle.

### isPoint {#isPoint--}
```
public boolean isPoint()
```

Checks if rectangle is point i.e. LLX is equal URX and LLY is equal URY.

**Returns:**
boolean value

### isTrivial {#isTrivial--}
```
public boolean isTrivial()
```

Checks if rectangle is trivial i.e. has zero size and position.

**Returns:**
boolean value

### join {#join-com.aspose.pdf.Rectangle-}
Joins rectangles.

### moveBy {#moveBy-double-double-}
```
public final void moveBy(double dx, double dy)
```

Shift rectangle by the specified deltas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dx |  | Value of shift by X axis. |
| dy |  | Value of shift by Y axis. |

### nearEquals {#nearEquals-com.aspose.pdf.Rectangle-double-}
Check if rectangles are near equal i.e. have near same (up to delta) position and sizes.

### parse {#parse-java.lang.String-}
Try to parse string and extract from it rectangle components llx, lly, urx, ury.

### rotate {#rotate-com.aspose.pdf.Rotation-}
Rotate rectangle by the specified angle.

### rotateAngle {#rotateAngle-int-}
```
public void rotateAngle(int angle)
```

Rotate rectangle by the specified angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle |  | Angle of rotation in degrees between 0 and 360. |

### setLLX {#setLLX-double-}
```
public void setLLX(double value)
```

Sets X-coordinate of lower - left corner.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setLLY {#setLLY-double-}
```
public void setLLY(double value)
```

Sets Y - coordinate of lower-left corner.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setURX {#setURX-double-}
```
public void setURX(double value)
```

Sets X - coordinate of upper-right corner.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setURY {#setURY-double-}
```
public void setURY(double value)
```

Sets Y - coordinate of upper-right corner.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### toArray {#toArray-com.aspose.pdf.engine.data.ITrailerable-}


### toPoints {#toPoints--}
```
public final Point [] toPoints()
```

Converts rectangle into array of points ("QuadPoints").

**Returns:**
Array of points.

### toRect {#toRect--}
```
public Rectangle toRect()
```

Converts rectangle to instance of System.Drawing.Rectangle. Floating-point positions and size are truncated.

**Returns:**
Result of conversion.

### toString {#toString--}
```
public String toString()
```

Gets rectangle string representation.

**Returns:**
String has format llx,lly,urx,ury.
