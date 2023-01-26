---
title: PolygonAnnotation
second_title: Aspose.PDF for Java API Reference
description: Class representing polygon annotation.
type: docs
weight: 291
url: /java/com.aspose.pdf/polygonannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation), [com.aspose.pdf.PolyAnnotation](../../com.aspose.pdf/polyannotation)
```
public final class PolygonAnnotation extends PolyAnnotation
```

Class representing polygon annotation.
## Constructors

| Constructor | Description |
| --- | --- |
| [PolygonAnnotation(IDocument document, Point[] vertices)](#PolygonAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point---) | Constructor for using with Generator. |
| [PolygonAnnotation(Page page, Rectangle rect, Point[] vertices)](#PolygonAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point---) | Creates new Polygon annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object for annotation processing. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
### PolygonAnnotation(IDocument document, Point[] vertices) {#PolygonAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point---}
```
public PolygonAnnotation(IDocument document, Point[] vertices)
```


Constructor for using with Generator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document where annotation will be added. |
| vertices | [Point\[\]](../../com.aspose.pdf/point) | Array of points. |

### PolygonAnnotation(Page page, Rectangle rect, Point[] vertices) {#PolygonAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point---}
```
public PolygonAnnotation(Page page, Rectangle rect, Point[] vertices)
```


Creates new Polygon annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The annotation rectangle, defining the location of the annotation on the page. |
| vertices | [Point\[\]](../../com.aspose.pdf/point) | An array of polygon vertices points. |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor object for annotation processing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

### getAnnotationType() {#getAnnotationType--}
```
public int getAnnotationType()
```


Gets type of annotation.

**Returns:**
int - AnnotationType element
