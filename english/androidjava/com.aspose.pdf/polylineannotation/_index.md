---
title: PolylineAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents polyline annotation that is similar to polygon except that the first and last vertex are not implicitly connected.
type: docs
weight: 235
url: /java/com.aspose.pdf/polylineannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation), [com.aspose.pdf.PolyAnnotation](../../com.aspose.pdf/polyannotation)
```
public final class PolylineAnnotation extends PolyAnnotation
```

Represents polyline annotation that is similar to polygon, except that the first and last vertex are not implicitly connected.
## Constructors

| Constructor | Description |
| --- | --- |
| [PolylineAnnotation(Page page, Rectangle rect, Point[] vertices)](#PolylineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point---) | Creates new Polyline annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [writeXfdf(System.Xml.XmlWriter writer)](#writeXfdf-com.aspose.ms.System.Xml.XmlWriter-) |  |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
### PolylineAnnotation(Page page, Rectangle rect, Point[] vertices) {#PolylineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point---}
```
public PolylineAnnotation(Page page, Rectangle rect, Point[] vertices)
```


Creates new Polyline annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The annotation rectangle, defining the location of the annotation on the page. |
| vertices | [Point\[\]](../../com.aspose.pdf/point) | An array of polygon vertices points. |

### writeXfdf(System.Xml.XmlWriter writer) {#writeXfdf-com.aspose.ms.System.Xml.XmlWriter-}
```
public void writeXfdf(System.Xml.XmlWriter writer)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| writer | com.aspose.ms.System.Xml.XmlWriter |  |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor object to process the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

