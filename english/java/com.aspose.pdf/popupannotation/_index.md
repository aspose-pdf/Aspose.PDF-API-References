---
title: PopupAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents the pop-up annotation that displays text in a pop-up window for entry and editing.
type: docs
weight: 289
url: /java/com.aspose.pdf/popupannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation)
```
public final class PopupAnnotation extends Annotation
```

Represents the pop-up annotation that displays text in a pop-up window for entry and editing.
## Constructors

| Constructor | Description |
| --- | --- |
| [PopupAnnotation(IDocument document)](#PopupAnnotation-com.aspose.pdf.IDocument-) | Constructor. for using in Generator. |
| [PopupAnnotation(Page page, Rectangle rect)](#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new Popup annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [getOpen()](#getOpen--) | Gets a flag specifying whether the pop-up annotation should initially be displayed open. |
| [setOpen(boolean value)](#setOpen-boolean-) | Sets a flag specifying whether the pop-up annotation should initially be displayed open. |
| [getParent()](#getParent--) | Gets the parent annotation with which this pop-up annotation shall be associated. |
| [setParent(MarkupAnnotation value)](#setParent-com.aspose.pdf.MarkupAnnotation-) | Sets the parent annotation with which this pop-up annotation shall be associated. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
### PopupAnnotation(IDocument document) {#PopupAnnotation-com.aspose.pdf.IDocument-}
```
public PopupAnnotation(IDocument document)
```


Constructor. for using in Generator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document where new popup annotation will be created. |

### PopupAnnotation(Page page, Rectangle rect) {#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public PopupAnnotation(Page page, Rectangle rect)
```


Creates new Popup annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The annotation rectangle, defining the location of the annotation on the page. |

### getOpen() {#getOpen--}
```
public boolean getOpen()
```


Gets a flag specifying whether the pop-up annotation should initially be displayed open.

**Returns:**
boolean - boolean value
### setOpen(boolean value) {#setOpen-boolean-}
```
public void setOpen(boolean value)
```


Sets a flag specifying whether the pop-up annotation should initially be displayed open.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getParent() {#getParent--}
```
public Annotation getParent()
```


Gets the parent annotation with which this pop-up annotation shall be associated. If this entry is present, the parent annotation's Contents, M, C, and T entries shall override those of the pop-up annotation itself.

**Returns:**
[Annotation](../../com.aspose.pdf/annotation) - MarkupAnnotation object
### setParent(MarkupAnnotation value) {#setParent-com.aspose.pdf.MarkupAnnotation-}
```
public void setParent(MarkupAnnotation value)
```


Sets the parent annotation with which this pop-up annotation shall be associated. If this entry is present, the parent annotation's Contents, M, C, and T entries shall override those of the pop-up annotation itself.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarkupAnnotation](../../com.aspose.pdf/markupannotation) | MarkupAnnotation object |

### getAnnotationType() {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```


Gets type of annotation.

**Returns:**
[AnnotationType](../../com.aspose.pdf/annotationtype) - AnnotationType element
### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor object to process the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

