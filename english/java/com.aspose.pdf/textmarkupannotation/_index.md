---
title: TextMarkupAnnotation
second_title: Aspose.PDF for Java API Reference
description: Abstract base class for text markup annotations.
type: docs
weight: 378
url: /java/com.aspose.pdf/textmarkupannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation)
```
public abstract class TextMarkupAnnotation extends MarkupAnnotation
```

Abstract base class for text markup annotations.
## Methods

| Method | Description |
| --- | --- |
| [getQuadPoints()](#getQuadPoints--) | Gets an array of points specifying the coordinates of n quadrilaterals. |
| [setQuadPoints(Point[] value)](#setQuadPoints-com.aspose.pdf.Point---) | Sets an array of points specifying the coordinates of n quadrilaterals. |
| [changeAfterResize(Matrix transform)](#changeAfterResize-com.aspose.pdf.Matrix-) | Updates the QuadPoints, according to the matrix transform. |
| [getMarkedText()](#getMarkedText--) | Gets text under markup annotation as string. |
| [getMarkedTextFragments()](#getMarkedTextFragments--) | Gets text under markup annotation as  TextFragmentCollection . |
### getQuadPoints() {#getQuadPoints--}
```
public Point[] getQuadPoints()
```


Gets an array of points specifying the coordinates of n quadrilaterals. Each quadrilateral encompasses a word or group of contiguous words in the text underlying the annotation.

**Returns:**
com.aspose.pdf.Point[] - array of Point value
### setQuadPoints(Point[] value) {#setQuadPoints-com.aspose.pdf.Point---}
```
public void setQuadPoints(Point[] value)
```


Sets an array of points specifying the coordinates of n quadrilaterals. Each quadrilateral encompasses a word or group of contiguous words in the text underlying the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.pdf/point) | array of Point value |

### changeAfterResize(Matrix transform) {#changeAfterResize-com.aspose.pdf.Matrix-}
```
public void changeAfterResize(Matrix transform)
```


Updates the QuadPoints, according to the matrix transform.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.pdf/matrix) | Matrix that use for transformation (resize). |

### getMarkedText() {#getMarkedText--}
```
public String getMarkedText()
```


Gets text under markup annotation as string.

**Returns:**
java.lang.String - String containing text that is under markup annotation.
### getMarkedTextFragments() {#getMarkedTextFragments--}
```
public TextFragmentCollection getMarkedTextFragments()
```


Gets text under markup annotation as  TextFragmentCollection .

**Returns:**
[TextFragmentCollection](../../com.aspose.pdf/textfragmentcollection) -  TextFragmentCollection  containing  TextFragment s that is under markup annotation.
