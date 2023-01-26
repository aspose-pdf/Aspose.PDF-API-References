---
title: InkAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents a freehand scribble composed of one or more disjoint paths.
type: docs
weight: 182
url: /java/com.aspose.pdf/inkannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation)
```
public final class InkAnnotation extends MarkupAnnotation
```

Represents a freehand "scribble" composed of one or more disjoint paths.
## Constructors

| Constructor | Description |
| --- | --- |
| [InkAnnotation(IDocument document, List<Point[]> inkList)](#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-com.aspose.pdf.Point----) | Constructor for Ink annotation for Generator. |
| [InkAnnotation(Page page, Rectangle rect, List<Point[]> inkList)](#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-com.aspose.pdf.Point----) | Creates new Ink annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [getCapStyle()](#getCapStyle--) | get style of ink annotation line endings. |
| [setCapStyle(int value)](#setCapStyle-int-) | Set style of ink annotation line endings. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [getInkList()](#getInkList--) | Gets list of gestures that are independent lines which are represented by Point[] arrays. |
| [setInkList(List<Point[]> value)](#setInkList-java.util.List-com.aspose.pdf.Point----) | Sets list of gestures that are independent lines which are represented by Point[] arrays. |
| [updateAppearance()](#updateAppearance--) | Updates the Appearance, after text has been changed/moved. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
| [changeAfterResize(Matrix transform)](#changeAfterResize-com.aspose.pdf.Matrix-) | Updates the points in InkList, according to the matrix transform. |
### InkAnnotation(IDocument document, List<Point[]> inkList) {#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-com.aspose.pdf.Point----}
```
public InkAnnotation(IDocument document, List<Point[]> inkList)
```


Constructor for Ink annotation for Generator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document where ink annotation will be created. |
| inkList | java.util.List<com.aspose.pdf.Point[]> | An array of Point[] arrays, each representing a stroked path. |

### InkAnnotation(Page page, Rectangle rect, List<Point[]> inkList) {#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-com.aspose.pdf.Point----}
```
public InkAnnotation(Page page, Rectangle rect, List<Point[]> inkList)
```


Creates new Ink annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The annotation rectangle, defining the location of the annotation on the page. |
| inkList | java.util.List<com.aspose.pdf.Point[]> | An array of Point[] arrays, each representing a stroked path. |

### getCapStyle() {#getCapStyle--}
```
public int getCapStyle()
```


get style of ink annotation line endings.

**Returns:**
int - CapStyle element
### setCapStyle(int value) {#setCapStyle-int-}
```
public void setCapStyle(int value)
```


Set style of ink annotation line endings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | CapStyle element |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor object to process the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

### getInkList() {#getInkList--}
```
public List<Point[]> getInkList()
```


Gets list of gestures that are independent lines which are represented by Point[] arrays.

**Returns:**
java.util.List<com.aspose.pdf.Point[]> -  List  object
### setInkList(List<Point[]> value) {#setInkList-java.util.List-com.aspose.pdf.Point----}
```
public void setInkList(List<Point[]> value)
```


Sets list of gestures that are independent lines which are represented by Point[] arrays.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.aspose.pdf.Point[]> |  List  object |

### updateAppearance() {#updateAppearance--}
```
public void updateAppearance()
```


Updates the Appearance, after text has been changed/moved.

### getAnnotationType() {#getAnnotationType--}
```
public int getAnnotationType()
```


Gets type of annotation.

**Returns:**
int - AnnotationType element
### changeAfterResize(Matrix transform) {#changeAfterResize-com.aspose.pdf.Matrix-}
```
public void changeAfterResize(Matrix transform)
```


Updates the points in InkList, according to the matrix transform.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.pdf/matrix) | Matrix specifying the transformation. |

