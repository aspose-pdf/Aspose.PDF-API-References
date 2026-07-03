---
title: InkAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents a freehand \"scribble\" composed of one or more disjoint paths.
type: docs
weight: 2430
url: /java/com.aspose.pdf/inkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.InkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class InkAnnotation extends MarkupAnnotation
```

Represents a freehand "scribble" composed of one or more disjoint paths.

## Constructors

| Constructor | Description |
| --- | --- |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-) | Constructor for Ink annotation for Generator. |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-) | Creates new Ink annotation on the specified page. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Updates the points in InkList, according to the matrix transform. |
| [getAnnotationType](#getAnnotationType--) | Gets type of annotation. |
| [getCapStyle](#getCapStyle--) | get style of ink annotation line endings. |
| [getInkList](#getInkList--) | <p> Gets list of gestures that are independent lines which are represented by Point[] arrays. </p> |
| [setCapStyle](#setCapStyle-com.aspose.pdf.CapStyle-) | Set style of ink annotation line endings. |
| [setInkList](#setInkList-java.util.List-) | Sets list of gestures that are independent lines which are represented by Point[] arrays. |
| [updateAppearance](#updateAppearance--) | Updates the Appearance, after text has been changed/moved. |

### InkAnnotation {#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-}
Constructor for Ink annotation for Generator.

### InkAnnotation {#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-}
Creates new Ink annotation on the specified page.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepts visitor object to process the annotation.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Updates the points in InkList, according to the matrix transform.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Gets type of annotation.

**Returns:**
AnnotationType element @see AnnotationType

### getCapStyle {#getCapStyle--}
```
public CapStyle getCapStyle()
```

get style of ink annotation line endings.

**Returns:**
CapStyle element @see CapStyle

### getInkList {#getInkList--}
```
public List < Point []> getInkList()
```

<p> Gets list of gestures that are independent lines which are represented by Point[] arrays. </p>

**Returns:**
{@code List<Point[]>} object

### setCapStyle {#setCapStyle-com.aspose.pdf.CapStyle-}
Set style of ink annotation line endings.

### setInkList {#setInkList-java.util.List-}
Sets list of gestures that are independent lines which are represented by Point[] arrays.

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

Updates the Appearance, after text has been changed/moved.
