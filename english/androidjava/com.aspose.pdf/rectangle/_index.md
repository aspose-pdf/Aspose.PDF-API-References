---
title: Rectangle
second_title: Aspose.PDF for Java API Reference
description: Class represents rectangle.
type: docs
weight: 244
url: /java/com.aspose.pdf/rectangle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public final class Rectangle implements Comparable
```

Class represents rectangle.
## Constructors

| Constructor | Description |
| --- | --- |
| [Rectangle(double llx, double lly, double urx, double ury)](#Rectangle-double-double-double-double-) | Constructor of Rectangle. |
## Fields

| Field | Description |
| --- | --- |
| [Empty](#Empty) | Empty rectangle |
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Width of rectangle. |
| [getHeight()](#getHeight--) | Height of rectangle. |
| [getLLX()](#getLLX--) | X-coordinate of lower - left corner. |
| [setLLX(double value)](#setLLX-double-) |  |
| [getLLY()](#getLLY--) | Y - coordinate of lower-left corner. |
| [setLLY(double value)](#setLLY-double-) |  |
| [getURX()](#getURX--) | X - coordinate of upper-right corner. |
| [setURX(double value)](#setURX-double-) |  |
| [getURY()](#getURY--) | Y - coordinate of upper-right corner. |
| [setURY(double value)](#setURY-double-) |  |
| [toRect()](#toRect--) |  |
| [fromRect(Rect src)](#fromRect-android.graphics.Rect-) |  |
| [fromRect(Rectangle src)](#fromRect-com.aspose.pdf.java.awt.Rectangle-) |  |
| [toArray(ITrailerable trailerable)](#toArray-com.aspose.pdf.engine.data.ITrailerable-) |  |
| [toString()](#toString--) | Gets rectangle string representation. |
| [parse(String value)](#parse-java.lang.String-) | Try to parse string and extract from it rectangle components llx, lly, urx, ury. |
| [getTrivial()](#getTrivial--) | Initializes trivial rectangle i.e. rectangle with zero position and size. |
| [isTrivial()](#isTrivial--) | Checks if rectangle is trivial i.e. has zero size and position. |
| [isEmpty()](#isEmpty--) | Checks if rectangle is empty. |
| [isPoint()](#isPoint--) | Checks if rectangle is point i.e. |
| [equals(Object other)](#equals-java.lang.Object-) | Check if rectangles are equal i.e. hase same position and sizes. |
| [intersect(Rectangle otherRect)](#intersect-com.aspose.pdf.Rectangle-) | Intersects rectangles |
| [rotate(int angle)](#rotate-int-) | Rotate rectangle by the specified angle. |
| [compareTo(Object arg0)](#compareTo-java.lang.Object-) |  |
| [clone()](#clone--) | Clones the Rectangle object. |
| [deepClone()](#deepClone--) | Clones the Rectangle object. |
| [getEmpty()](#getEmpty--) | Gets empty rectangle |
| [isIntersect(Rectangle otherRect)](#isIntersect-com.aspose.pdf.Rectangle-) | Determines whether this rectangle intersects with other rectangle. |
| [_Intersect(Rectangle otherRect)](#-Intersect-com.aspose.pdf.Rectangle-) | Intersects rectangles. |
| [contains(Point point)](#contains-com.aspose.pdf.Point-) | Determinces whether given point is inside of the rectangle. |
| [center()](#center--) | Returncs coordinates of center of the rectangle. |
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

### Empty {#Empty}
```
public static Rectangle Empty
```


Empty rectangle

### getWidth() {#getWidth--}
```
public double getWidth()
```


Width of rectangle.

**Returns:**
double
### getHeight() {#getHeight--}
```
public double getHeight()
```


Height of rectangle.

**Returns:**
double
### getLLX() {#getLLX--}
```
public double getLLX()
```


X-coordinate of lower - left corner.

**Returns:**
double
### setLLX(double value) {#setLLX-double-}
```
public void setLLX(double value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getLLY() {#getLLY--}
```
public double getLLY()
```


Y - coordinate of lower-left corner.

**Returns:**
double
### setLLY(double value) {#setLLY-double-}
```
public void setLLY(double value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getURX() {#getURX--}
```
public double getURX()
```


X - coordinate of upper-right corner.

**Returns:**
double
### setURX(double value) {#setURX-double-}
```
public void setURX(double value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getURY() {#getURY--}
```
public double getURY()
```


Y - coordinate of upper-right corner.

**Returns:**
double
### setURY(double value) {#setURY-double-}
```
public void setURY(double value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### toRect() {#toRect--}
```
public Rect toRect()
```




**Returns:**
android.graphics.Rect
### fromRect(Rect src) {#fromRect-android.graphics.Rect-}
```
public static Rectangle fromRect(Rect src)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | android.graphics.Rect |  |

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
### fromRect(Rectangle src) {#fromRect-com.aspose.pdf.java.awt.Rectangle-}
```
public static Rectangle fromRect(Rectangle src)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | [Rectangle](../../com.aspose.pdf.java.awt/rectangle) |  |

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
### toArray(ITrailerable trailerable) {#toArray-com.aspose.pdf.engine.data.ITrailerable-}
```
public PdfArray toArray(ITrailerable trailerable)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| trailerable | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) |  |

**Returns:**
[PdfArray](../../com.aspose.pdf.engine.data/pdfarray)
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
### getTrivial() {#getTrivial--}
```
public static Rectangle getTrivial()
```


Initializes trivial rectangle i.e. rectangle with zero position and size.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
### isTrivial() {#isTrivial--}
```
public boolean isTrivial()
```


Checks if rectangle is trivial i.e. has zero size and position.

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Checks if rectangle is empty.

**Returns:**
boolean - 
### isPoint() {#isPoint--}
```
public boolean isPoint()
```


Checks if rectangle is point i.e. LLX is equal URX and LLY is equal URY.

**Returns:**
boolean - 
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Check if rectangles are equal i.e. hase same position and sizes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | java.lang.Object | Rectangle which will be compared. |

**Returns:**
boolean - True if rectangles are eqals, false otherwise.
### intersect(Rectangle otherRect) {#intersect-com.aspose.pdf.Rectangle-}
```
public void intersect(Rectangle otherRect)
```


Intersects rectangles

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| otherRect | [Rectangle](../../com.aspose.pdf/rectangle) |  |

### rotate(int angle) {#rotate-int-}
```
public void rotate(int angle)
```


Rotate rectangle by the specified angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | int | Angle of rotation. Member of Rotation enumeration. |

### compareTo(Object arg0) {#compareTo-java.lang.Object-}
```
public int compareTo(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
int
### clone() {#clone--}
```
public Object clone()
```


Clones the Rectangle object.

**Returns:**
java.lang.Object - 
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clones the Rectangle object.

**Returns:**
java.lang.Object - Clone object.
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Gets empty rectangle

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - new Rectangle object
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
### _Intersect(Rectangle otherRect) {#-Intersect-com.aspose.pdf.Rectangle-}
```
public void _Intersect(Rectangle otherRect)
```


Intersects rectangles. Obsolete method. Please use Intersect instead.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| otherRect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |

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
