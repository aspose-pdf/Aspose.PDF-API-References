---
title: TextMarkupAnnotation
second_title: Aspose.PDF for Java API Reference
description: Abstract base class for text markup annotations.
type: docs
weight: 301
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
### getQuadPoints() {#getQuadPoints--}
```
public Point[] getQuadPoints()
```


Gets an array of points specifying the coordinates of n quadrilaterals. Each quadrilateral encompasses a word or group of contiguous words in the text underlying the annotation.

**Returns:**
com.aspose.pdf.Point[]
### setQuadPoints(Point[] value) {#setQuadPoints-com.aspose.pdf.Point---}
```
public void setQuadPoints(Point[] value)
```


Sets an array of points specifying the coordinates of n quadrilaterals. Each quadrilateral encompasses a word or group of contiguous words in the text underlying the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.pdf/point) |  |

