---
title: PolyAnnotation
second_title: Aspose.PDF for Java API Reference
description: Abstract base class for poly-annotations.
type: docs
weight: 289
url: /java/com.aspose.pdf/polyannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation)
```
public abstract class PolyAnnotation extends MarkupAnnotation
```

Abstract base class for poly-annotations.
## Methods

| Method | Description |
| --- | --- |
| [getMeasure()](#getMeasure--) | Measure units specified for this annotation. |
| [setMeasure(Measure value)](#setMeasure-com.aspose.pdf.Measure-) | Measure units specified for this annotation. |
| [getVertices()](#getVertices--) | Gets an array of points representing the horizontal and vertical coordinates of each vertex. |
| [setVertices(Point[] value)](#setVertices-com.aspose.pdf.Point---) | Sets an array of points representing the horizontal and vertical coordinates of each vertex. |
| [getInteriorColor()](#getInteriorColor--) | Gets the interior color with which to fill the annotation's line endings. |
| [setInteriorColor(Color value)](#setInteriorColor-com.aspose.pdf.Color-) | Sets the interior color with which to fill the annotation's line endings. |
| [getStartingStyle()](#getStartingStyle--) | Gets the style of first line ending. |
| [setStartingStyle(int value)](#setStartingStyle-int-) | Sets the style of first line ending. |
| [getEndingStyle()](#getEndingStyle--) | Gets the style of second line ending. |
| [setEndingStyle(int value)](#setEndingStyle-int-) | Sets the style of second line ending. |
| [getIntent()](#getIntent--) | Gets the intent of the polygon or polyline annotation. |
| [setIntent(int value)](#setIntent-int-) | Sets the intent of the polygon or polyline annotation. |
| [changeAfterResize(Matrix transform)](#changeAfterResize-com.aspose.pdf.Matrix-) | Updates the points in Vertices, according to the matrix transform. |
### getMeasure() {#getMeasure--}
```
public Measure getMeasure()
```


Measure units specified for this annotation.

**Returns:**
[Measure](../../com.aspose.pdf/measure) - Measure instance
### setMeasure(Measure value) {#setMeasure-com.aspose.pdf.Measure-}
```
public void setMeasure(Measure value)
```


Measure units specified for this annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Measure](../../com.aspose.pdf/measure) | Measure instance |

### getVertices() {#getVertices--}
```
public Point[] getVertices()
```


Gets an array of points representing the horizontal and vertical coordinates of each vertex.

**Returns:**
com.aspose.pdf.Point[] - array of Point value
### setVertices(Point[] value) {#setVertices-com.aspose.pdf.Point---}
```
public void setVertices(Point[] value)
```


Sets an array of points representing the horizontal and vertical coordinates of each vertex.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.pdf/point) | array of Point value |

### getInteriorColor() {#getInteriorColor--}
```
public Color getInteriorColor()
```


Gets the interior color with which to fill the annotation's line endings.

**Returns:**
[Color](../../com.aspose.pdf/color) - Color object
### setInteriorColor(Color value) {#setInteriorColor-com.aspose.pdf.Color-}
```
public void setInteriorColor(Color value)
```


Sets the interior color with which to fill the annotation's line endings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | Color object |

### getStartingStyle() {#getStartingStyle--}
```
public int getStartingStyle()
```


Gets the style of first line ending.

**Returns:**
int - LineEnding element
### setStartingStyle(int value) {#setStartingStyle-int-}
```
public void setStartingStyle(int value)
```


Sets the style of first line ending.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | LineEnding element |

### getEndingStyle() {#getEndingStyle--}
```
public int getEndingStyle()
```


Gets the style of second line ending.

**Returns:**
int - LineEnding element
### setEndingStyle(int value) {#setEndingStyle-int-}
```
public void setEndingStyle(int value)
```


Sets the style of second line ending.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | LineEnding element |

### getIntent() {#getIntent--}
```
public int getIntent()
```


Gets the intent of the polygon or polyline annotation.

**Returns:**
int - PolyIntent element
### setIntent(int value) {#setIntent-int-}
```
public void setIntent(int value)
```


Sets the intent of the polygon or polyline annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | PolyIntent element |

### changeAfterResize(Matrix transform) {#changeAfterResize-com.aspose.pdf.Matrix-}
```
public void changeAfterResize(Matrix transform)
```


Updates the points in Vertices, according to the matrix transform.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.pdf/matrix) | Matrix specifying the transformation. |

