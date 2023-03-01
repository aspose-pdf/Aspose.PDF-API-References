---
title: Rectangle
second_title: Aspose.PDF for Java API Reference
description: Class represents rectangle.
type: docs
weight: 300
url: /java/com.aspose.pdf/rectangle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, java.lang.Cloneable
```
public final class Rectangle implements Comparable<Object>, Cloneable
```

Class represents rectangle.
## Constructors

| Constructor | Description |
| --- | --- |
| [Rectangle(double llx, double lly, double urx, double ury)](#Rectangle-double-double-double-double-) | Constructor of Rectangle. |
| [Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates)](#Rectangle-double-double-double-double-boolean-) | Constructor of Rectangle. |
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Gets width of rectangle. |
| [getHeight()](#getHeight--) | Get height of rectangle. |
| [getLLX()](#getLLX--) | Gets X-coordinate of lower - left corner. |
| [setLLX(double value)](#setLLX-double-) | Sets X-coordinate of lower - left corner. |
| [getLLY()](#getLLY--) | Gets Y - coordinate of lower-left corner. |
| [setLLY(double value)](#setLLY-double-) | Sets Y - coordinate of lower-left corner. |
| [getURX()](#getURX--) | Gets X - coordinate of upper-right corner. |
| [setURX(double value)](#setURX-double-) | Sets X - coordinate of upper-right corner. |
| [getURY()](#getURY--) | Gets Y - coordinate of upper-right corner. |
| [setURY(double value)](#setURY-double-) | Sets Y - coordinate of upper-right corner. |
| [toRect()](#toRect--) | Converts rectangle to instance of System.Drawing.Rectangle. |
| [fromRect(Rectangle src)](#fromRect-java.awt.Rectangle-) | Initializes new rectangle from given instance of System.Drawing.Rectangle. |
| [toString()](#toString--) | Gets rectangle string representation. |
| [parse(String value)](#parse-java.lang.String-) | Try to parse string and extract from it rectangle components llx, lly, urx, ury. |
| [getEmpty()](#getEmpty--) | Gets empty rectangle |
| [getTrivial()](#getTrivial--) | Initializes trivial rectangle i.e. rectangle with zero position and size. |
| [isTrivial()](#isTrivial--) | Checks if rectangle is trivial i.e. has zero size and position. |
| [isEmpty()](#isEmpty--) | Checks if rectangle is empty. |
| [isPoint()](#isPoint--) | Checks if rectangle is point i.e. |
| [equals(Object other)](#equals-java.lang.Object-) | Check if rectangles are equal i.e. have same position and sizes. |
| [nearEquals(Rectangle other, double delta)](#nearEquals-com.aspose.pdf.Rectangle-double-) | Check if rectangles are near equal i.e. have near same (up to delta) position and sizes. |
| [hashCode()](#hashCode--) | Returns a hash code value for the object. |
| [intersect(Rectangle otherRect)](#intersect-com.aspose.pdf.Rectangle-) | Intersects to rectangles. |
| [join(Rectangle otherRect)](#join-com.aspose.pdf.Rectangle-) | Joins rectangles. |
| [_Intersect(Rectangle otherRect)](#-Intersect-com.aspose.pdf.Rectangle-) | Intersects rectangles. |
| [isIntersect(Rectangle otherRect)](#isIntersect-com.aspose.pdf.Rectangle-) | Determines whether this rectangle intersects with other rectangle. |
| [contains(Point point)](#contains-com.aspose.pdf.Point-) | Determinces whether given point is inside of the rectangle. |
| [center()](#center--) | Returncs coordinates of center of the rectangle. |
| [isInclude(Rectangle otherRect, double rotationAngle)](#isInclude-com.aspose.pdf.Rectangle-double-) | Checks that this rectangle includes whole another rectangle. |
| [rotate(int angle)](#rotate-int-) | Rotate rectangle by the specified angle. |
| [rotateAngle(int angle)](#rotateAngle-int-) | Rotate rectangle by the specified angle. |
| [compareTo(Object arg0)](#compareTo-java.lang.Object-) | CompareTo |
| [clone()](#clone--) | Clones the Rectangle object. |
| [deepClone()](#deepClone--) | Clones the Rectangle object. |
| [toPoints()](#toPoints--) | Converts rectangle into array of points ("QuadPoints"). |
### Rectangle(double llx, double lly, double urx, double ury) {#Rectangle-double-double-double-double-}
```
public Rectangle(double llx, double lly, double urx, double ury)
```


Constructor of Rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| llx | double | X of lower left corner. |
| lly | double | Y of lower left corner. |
| urx | double | X of upper right corner. |
| ury | double | Y of upper right corner. |

### Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates) {#Rectangle-double-double-double-double-boolean-}
```
public Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates)
```


Constructor of Rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| llx | double | X of lower left corner. |
| lly | double | Y of lower left corner. |
| urx | double | X of upper right corner. |
| ury | double | Y of upper right corner. |
| normalizeCoordinates | boolean | Normalize coordinates of rectangle. |

### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets width of rectangle.

**Returns:**
double - double value
### getHeight() {#getHeight--}
```
public double getHeight()
```


Get height of rectangle.

**Returns:**
double - double value
### getLLX() {#getLLX--}
```
public double getLLX()
```


Gets X-coordinate of lower - left corner.

**Returns:**
double - double value
### setLLX(double value) {#setLLX-double-}
```
public void setLLX(double value)
```


Sets X-coordinate of lower - left corner.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getLLY() {#getLLY--}
```
public double getLLY()
```


Gets Y - coordinate of lower-left corner.

**Returns:**
double - double value
### setLLY(double value) {#setLLY-double-}
```
public void setLLY(double value)
```


Sets Y - coordinate of lower-left corner.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getURX() {#getURX--}
```
public double getURX()
```


Gets X - coordinate of upper-right corner.

**Returns:**
double - double value
### setURX(double value) {#setURX-double-}
```
public void setURX(double value)
```


Sets X - coordinate of upper-right corner.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getURY() {#getURY--}
```
public double getURY()
```


Gets Y - coordinate of upper-right corner.

**Returns:**
double - double value
### setURY(double value) {#setURY-double-}
```
public void setURY(double value)
```


Sets Y - coordinate of upper-right corner.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### toRect() {#toRect--}
```
public Rectangle toRect()
```


Converts rectangle to instance of System.Drawing.Rectangle. Floating-point positions and size are truncated.

**Returns:**
[Rectangle](../../java.awt/rectangle) - Result of conversion.
### fromRect(Rectangle src) {#fromRect-java.awt.Rectangle-}
```
public static Rectangle fromRect(Rectangle src)
```


Initializes new rectangle from given instance of System.Drawing.Rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | java.awt.Rectangle | Source rectangle which position and size will be set to new rectangle. |

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - New rectangle.
### toString() {#toString--}
```
public String toString()
```


Gets rectangle string representation.

**Returns:**
java.lang.String - String has format llx,lly,urx,ury.
### parse(String value) {#parse-java.lang.String-}
```
public static Rectangle parse(String value)
```


Try to parse string and extract from it rectangle components llx, lly, urx, ury.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String to parse. |

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle object.
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Gets empty rectangle

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - new Rectangle object
### getTrivial() {#getTrivial--}
```
public static Rectangle getTrivial()
```


Initializes trivial rectangle i.e. rectangle with zero position and size.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - new Rectangle object
### isTrivial() {#isTrivial--}
```
public boolean isTrivial()
```


Checks if rectangle is trivial i.e. has zero size and position.

**Returns:**
boolean - boolean value
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Checks if rectangle is empty.

**Returns:**
boolean - boolean value
### isPoint() {#isPoint--}
```
public boolean isPoint()
```


Checks if rectangle is point i.e. LLX is equal URX and LLY is equal URY.

**Returns:**
boolean - boolean value
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Check if rectangles are equal i.e. have same position and sizes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | java.lang.Object | Rectangle which will be compared. |

**Returns:**
boolean - True if rectangles are equals, false otherwise.
### nearEquals(Rectangle other, double delta) {#nearEquals-com.aspose.pdf.Rectangle-double-}
```
public boolean nearEquals(Rectangle other, double delta)
```


Check if rectangles are near equal i.e. have near same (up to delta) position and sizes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle which will be compared. |
| delta | double | Value of comparation tollerance. |

**Returns:**
boolean - True if rectangles are equals, false otherwise.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code value for the object. This method is supported for the benefit of hash tables such as those provided by java.util.HashMap.

The general contract of  hashCode  is:

 *  Whenever it is invoked on the same object more than once during an execution of a Java application, the  hashCode  method must consistently return the same integer, provided no information used in  equals  comparisons on the object is modified. This integer need not remain consistent from one execution of an application to another execution of the same application.
 *  If two objects are equal according to the  equals(Object)  method, then calling the  hashCode  method on each of the two objects must produce the same integer result.
 *  It is *not* required that if two objects are unequal according to the java.lang.Object\#equals(java.lang.Object)\#equals(java.lang.Object) method, then calling the  hashCode  method on each of the two objects must produce distinct integer results. However, the programmer should be aware that producing distinct integer results for unequal objects may improve the performance of hash tables.

As much as is reasonably practical, the hashCode method defined by class  Object  does return distinct integers for distinct objects. (This is typically implemented by converting the internal address of the object into an integer, but this implementation technique is not required by the JavaTM programming language.)

**Returns:**
int - a hash code value for this object.
### intersect(Rectangle otherRect) {#intersect-com.aspose.pdf.Rectangle-}
```
public Rectangle intersect(Rectangle otherRect)
```


Intersects to rectangles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| otherRect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle to which this recatangle be intersected. |

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Intersection of rectangles; null if rectangles are not intersected.
### join(Rectangle otherRect) {#join-com.aspose.pdf.Rectangle-}
```
public Rectangle join(Rectangle otherRect)
```


Joins rectangles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| otherRect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle to which this rectangle be joined. |

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Described rectangle.
### _Intersect(Rectangle otherRect) {#-Intersect-com.aspose.pdf.Rectangle-}
```
public void _Intersect(Rectangle otherRect)
```


Intersects rectangles. Obsolete method. Please use Intersect instead.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| otherRect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |

### isIntersect(Rectangle otherRect) {#isIntersect-com.aspose.pdf.Rectangle-}
```
public boolean isIntersect(Rectangle otherRect)
```


Determines whether this rectangle intersects with other rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| otherRect | [Rectangle](../../com.aspose.pdf/rectangle) | Intersection will be tested with specified rectangle. |

**Returns:**
boolean - True if this rectangle intersects with specified rectangle. Otherwise false.
### contains(Point point) {#contains-com.aspose.pdf.Point-}
```
public boolean contains(Point point)
```


Determinces whether given point is inside of the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.pdf/point) | Point to check. |

**Returns:**
boolean - True if point is inside of the recatngle.
### center() {#center--}
```
public Point center()
```


Returncs coordinates of center of the rectangle.

**Returns:**
[Point](../../com.aspose.pdf/point) - Point which is center of the rectangle.
### isInclude(Rectangle otherRect, double rotationAngle) {#isInclude-com.aspose.pdf.Rectangle-double-}
```
public boolean isInclude(Rectangle otherRect, double rotationAngle)
```


Checks that this rectangle includes whole another rectangle. I.e. whole another rectangle is inside this rectangle. Difference with IsIntersect method is that IsIntersect will true for partly intersected rectangles but IsInclude will false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| otherRect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle for which including is checked. |
| rotationAngle | double | Rotation angle of another rectangle in radians. |

**Returns:**
boolean - True if this rectangle includes whole specified rectangle. Otherwise false.
### rotate(int angle) {#rotate-int-}
```
public void rotate(int angle)
```


Rotate rectangle by the specified angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | int | Angle of rotation. Member of Rotation enumeration. |

### rotateAngle(int angle) {#rotateAngle-int-}
```
public void rotateAngle(int angle)
```


Rotate rectangle by the specified angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | int | Angle of rotation in degrees between 0 and 360. |

### compareTo(Object arg0) {#compareTo-java.lang.Object-}
```
public int compareTo(Object arg0)
```


CompareTo

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object | Object for compare |

**Returns:**
int - int value
### clone() {#clone--}
```
public Object clone()
```


Clones the Rectangle object.

**Returns:**
java.lang.Object - Clone object.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clones the Rectangle object.

**Returns:**
java.lang.Object - Clone object.
### toPoints() {#toPoints--}
```
public final Point[] toPoints()
```


Converts rectangle into array of points ("QuadPoints").

**Returns:**
com.aspose.pdf.Point[] - Array of points.
