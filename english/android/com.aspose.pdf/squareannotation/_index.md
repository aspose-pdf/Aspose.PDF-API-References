---
title: SquareAnnotation
second_title: Aspose.PDF for Java API Reference
description: Class representing square annotation.
type: docs
weight: 270
url: /java/com.aspose.pdf/squareannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation), [com.aspose.pdf.CommonFigureAnnotation](../../com.aspose.pdf/commonfigureannotation)
```
public final class SquareAnnotation extends CommonFigureAnnotation
```

Class representing square annotation.
## Constructors

| Constructor | Description |
| --- | --- |
| [SquareAnnotation(Page page, Rectangle rect)](#SquareAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new Square annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [writeXfdf(System.Xml.XmlWriter writer)](#writeXfdf-com.aspose.ms.System.Xml.XmlWriter-) |  |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor to process annotation. |
### SquareAnnotation(Page page, Rectangle rect) {#SquareAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public SquareAnnotation(Page page, Rectangle rect)
```


Creates new Square annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The annotation rectangle, defining the location of the annotation on the page. |

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


Accepts visitor to process annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

