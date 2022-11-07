---
title: InkAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents a freehand scribble composed of one or more disjoint paths.
type: docs
weight: 151
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
| [InkAnnotation(Page page, Rectangle rect, System.Collections.IList inkList)](#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.ms.System.Collections.IList-) | Creates new Ink annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [getInkList()](#getInkList--) | Gets or sets list of gestures that are independent lines which are represented by Point[] arrays. |
| [setInkList(System.Collections.IList value)](#setInkList-com.aspose.ms.System.Collections.IList-) |  |
### InkAnnotation(Page page, Rectangle rect, System.Collections.IList inkList) {#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.ms.System.Collections.IList-}
```
public InkAnnotation(Page page, Rectangle rect, System.Collections.IList inkList)
```


Creates new Ink annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The annotation rectangle, defining the location of the annotation on the page. |
| inkList | com.aspose.ms.System.Collections.IList | An array of Point[] arrays, each representing a stroked path. |

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
public System.Collections.IList getInkList()
```


Gets or sets list of gestures that are independent lines which are represented by Point[] arrays.

**Returns:**
com.aspose.ms.System.Collections.IList
### setInkList(System.Collections.IList value) {#setInkList-com.aspose.ms.System.Collections.IList-}
```
public void setInkList(System.Collections.IList value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.IList |  |

