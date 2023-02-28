---
title: UnderlineAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents an underline annotation that appears as an underline in the text of the document.
type: docs
weight: 394
url: /java/com.aspose.pdf/underlineannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation), [com.aspose.pdf.TextMarkupAnnotation](../../com.aspose.pdf/textmarkupannotation)
```
public final class UnderlineAnnotation extends TextMarkupAnnotation
```

Represents an underline annotation that appears as an underline in the text of the document.
## Constructors

| Constructor | Description |
| --- | --- |
| [UnderlineAnnotation(Page page, Rectangle rect)](#UnderlineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new Underline annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
### UnderlineAnnotation(Page page, Rectangle rect) {#UnderlineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public UnderlineAnnotation(Page page, Rectangle rect)
```


Creates new Underline annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The annotation rectangle, defining the location of the annotation on the page. |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor object to process the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

### getAnnotationType() {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```


Gets type of annotation.

**Returns:**
[AnnotationType](../../com.aspose.pdf/annotationtype) - AnnotationType element
