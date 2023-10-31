---
title: CircleAnnotation
second_title: Aspose.PDF for Java API Reference
description: Class representing Circle annotation.
type: docs
weight: 58
url: /java/com.aspose.pdf/circleannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation), [com.aspose.pdf.CommonFigureAnnotation](../../com.aspose.pdf/commonfigureannotation)
```
public final class CircleAnnotation extends CommonFigureAnnotation
```

Class representing Circle annotation.
## Constructors

| Constructor | Description |
| --- | --- |
| [CircleAnnotation(IDocument document)](#CircleAnnotation-com.aspose.pdf.IDocument-) | Constructor for Circle annotation. |
| [CircleAnnotation(Page page, Rectangle rect)](#CircleAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new Circle annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
### CircleAnnotation(IDocument document) {#CircleAnnotation-com.aspose.pdf.IDocument-}
```
public CircleAnnotation(IDocument document)
```


Constructor for Circle annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document where annotation will be created. |

### CircleAnnotation(Page page, Rectangle rect) {#CircleAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public CircleAnnotation(Page page, Rectangle rect)
```


Creates new Circle annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Required rectangle that sets annotation's border. |

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
