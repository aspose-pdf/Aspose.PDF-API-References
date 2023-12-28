---
title: StrikeOutAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents a strikeout annotation that appears as a strikeout in the text of the document.
type: docs
weight: 343
url: /java/com.aspose.pdf/strikeoutannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation), [com.aspose.pdf.TextMarkupAnnotation](../../com.aspose.pdf/textmarkupannotation)
```
public final class StrikeOutAnnotation extends TextMarkupAnnotation
```

Represents a strikeout annotation that appears as a strikeout in the text of the document.
## Constructors

| Constructor | Description |
| --- | --- |
| [StrikeOutAnnotation(Page page, Rectangle rect)](#StrikeOutAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new StrikeOut annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
### StrikeOutAnnotation(Page page, Rectangle rect) {#StrikeOutAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public StrikeOutAnnotation(Page page, Rectangle rect)
```


Creates new StrikeOut annotation on the specified page.

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
