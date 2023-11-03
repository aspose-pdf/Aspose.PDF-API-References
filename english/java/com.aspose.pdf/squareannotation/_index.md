---
title: SquareAnnotation
second_title: Aspose.PDF for Java API Reference
description: Class representing square annotation.
type: docs
weight: 336
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
| [SquareAnnotation(IDocument document)](#SquareAnnotation-com.aspose.pdf.IDocument-) | Constructor for using with Generator. |
| [SquareAnnotation(Page page, Rectangle rect)](#SquareAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new Square annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor to process annotation. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
### SquareAnnotation(IDocument document) {#SquareAnnotation-com.aspose.pdf.IDocument-}
```
public SquareAnnotation(IDocument document)
```


Constructor for using with Generator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Documennt where annotation will be created. |

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

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor to process annotation.

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
