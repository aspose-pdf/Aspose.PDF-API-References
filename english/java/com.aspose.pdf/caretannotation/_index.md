---
title: CaretAnnotation
second_title: Aspose.PDF for Java API Reference
description: Class representing Caret annotation.
type: docs
weight: 48
url: /java/com.aspose.pdf/caretannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation)
```
public final class CaretAnnotation extends MarkupAnnotation
```

Class representing Caret annotation.
## Constructors

| Constructor | Description |
| --- | --- |
| [CaretAnnotation(IDocument document)](#CaretAnnotation-com.aspose.pdf.IDocument-) | Constructor for usign in Generator. |
| [CaretAnnotation(Page page, Rectangle rect)](#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new Caret annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
| [getFrame()](#getFrame--) | Gets caret rectangle. |
| [setFrame(Rectangle value)](#setFrame-com.aspose.pdf.Rectangle-) | Sets caret rectangle. |
| [getSymbol()](#getSymbol--) | Gets symbol associated with caret. |
| [setSymbol(int value)](#setSymbol-int-) | Sets output page size for import. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
### CaretAnnotation(IDocument document) {#CaretAnnotation-com.aspose.pdf.IDocument-}
```
public CaretAnnotation(IDocument document)
```


Constructor for usign in Generator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document where annotation will be created. |

### CaretAnnotation(Page page, Rectangle rect) {#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public CaretAnnotation(Page page, Rectangle rect)
```


Creates new Caret annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Required rectangle that sets annotation's border. |

### getAnnotationType() {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```


Gets type of annotation.

**Returns:**
[AnnotationType](../../com.aspose.pdf/annotationtype) - AnnotationType element
### getFrame() {#getFrame--}
```
public Rectangle getFrame()
```


Gets caret rectangle.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - caret rectangle.
### setFrame(Rectangle value) {#setFrame-com.aspose.pdf.Rectangle-}
```
public void setFrame(Rectangle value)
```


Sets caret rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | caret rectangle. |

### getSymbol() {#getSymbol--}
```
public int getSymbol()
```


Gets symbol associated with caret.

 CaretSymbol 

**Returns:**
int - CaretSymbol element
### setSymbol(int value) {#setSymbol-int-}
```
public void setSymbol(int value)
```


Sets output page size for import.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | CaretSymbol element |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor object to process the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

