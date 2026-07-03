---
title: TextMarkupAnnotation
second_title: Aspose.PDF for Java API Reference
description: Abstract base class for text markup annotations.
type: docs
weight: 5180
url: /java/com.aspose.pdf/textmarkupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextMarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class TextMarkupAnnotation extends MarkupAnnotation
```

Abstract base class for text markup annotations.

## Methods

| Method | Description |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Updates the QuadPoints, according to the matrix transform. |
| [getMarkedText](#getMarkedText--) | Gets text under markup annotation as string. |
| [getMarkedTextFragments](#getMarkedTextFragments--) | Gets text under markup annotation as {@code TextFragmentCollection}. |
| [getQuadPoints](#getQuadPoints--) | Gets an array of points specifying the coordinates of n quadrilaterals. Each quadrilateral encompasses a word or group of contiguous words in the text underlying the annotation. |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | Sets an array of points specifying the coordinates of n quadrilaterals. Each quadrilateral encompasses a word or group of contiguous words in the text underlying the annotation. |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Updates the QuadPoints, according to the matrix transform.

### getMarkedText {#getMarkedText--}
```
public String getMarkedText()
```

Gets text under markup annotation as string.

**Returns:**
String containing text that is under markup annotation.

### getMarkedTextFragments {#getMarkedTextFragments--}
```
public TextFragmentCollection getMarkedTextFragments()
```

Gets text under markup annotation as {@code TextFragmentCollection}.

**Returns:**
{@code TextFragmentCollection} containing {@code TextFragment}s that is under markup annotation.

### getQuadPoints {#getQuadPoints--}
```
public Point [] getQuadPoints()
```

Gets an array of points specifying the coordinates of n quadrilaterals. Each quadrilateral encompasses a word or group of contiguous words in the text underlying the annotation.

**Returns:**
array of Point value

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
Sets an array of points specifying the coordinates of n quadrilaterals. Each quadrilateral encompasses a word or group of contiguous words in the text underlying the annotation.
