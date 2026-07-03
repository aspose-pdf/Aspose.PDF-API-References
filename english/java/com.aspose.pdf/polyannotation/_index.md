---
title: PolyAnnotation
linktitle: PolyAnnotation
second_title: Aspose.PDF for Java API Reference
description: Abstract base class for poly-annotations.
type: docs
weight: 3890
url: /java/com.aspose.pdf/polyannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.PolyAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class PolyAnnotation extends MarkupAnnotation
```

Abstract base class for poly-annotations.

## Methods

| Method | Description |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Updates the points in Vertices, according to the matrix transform. |
| [getEndingStyle](#getEndingStyle--) | Gets the style of second line ending. |
| [getIntent](#getIntent--) | Gets the intent of the polygon or polyline annotation. |
| [getInteriorColor](#getInteriorColor--) | Gets the interior color with which to fill the annotation's line endings. |
| [getMeasure](#getMeasure--) | Measure units specified for this annotation. |
| [getStartingStyle](#getStartingStyle--) | Gets the style of first line ending. |
| [getVertices](#getVertices--) | Gets an array of points representing the horizontal and vertical coordinates of each vertex. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Sets the style of second line ending. |
| [setIntent](#setIntent-com.aspose.pdf.PolyIntent-) | Sets the intent of the polygon or polyline annotation. |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | Sets the interior color with which to fill the annotation's line endings. |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | Measure units specified for this annotation. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Sets the style of first line ending. |
| [setVertices](#setVertices-com.aspose.pdf.Point:A-) | Sets an array of points representing the horizontal and vertical coordinates of each vertex. |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Updates the points in Vertices, according to the matrix transform.

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Gets the style of second line ending.

**Returns:**
LineEnding element @see LineEnding

### getIntent {#getIntent--}
```
public PolyIntent getIntent()
```

Gets the intent of the polygon or polyline annotation.

**Returns:**
PolyIntent element @see PolyIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

Gets the interior color with which to fill the annotation's line endings.

**Returns:**
Color object

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

Measure units specified for this annotation.

**Returns:**
Measure instance

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

Gets the style of first line ending.

**Returns:**
LineEnding element @see LineEnding

### getVertices {#getVertices--}
```
public Point [] getVertices()
```

Gets an array of points representing the horizontal and vertical coordinates of each vertex.

**Returns:**
array of Point value

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Sets the style of second line ending.

### setIntent {#setIntent-com.aspose.pdf.PolyIntent-}
Sets the intent of the polygon or polyline annotation.

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
Sets the interior color with which to fill the annotation's line endings.

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
Measure units specified for this annotation.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Sets the style of first line ending.

### setVertices {#setVertices-com.aspose.pdf.Point:A-}
Sets an array of points representing the horizontal and vertical coordinates of each vertex.
