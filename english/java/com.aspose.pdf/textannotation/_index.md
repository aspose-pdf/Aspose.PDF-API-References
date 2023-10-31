---
title: TextAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents a text annotation that is a sticky note attached to a point in the PDF document.
type: docs
weight: 363
url: /java/com.aspose.pdf/textannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation)
```
public final class TextAnnotation extends MarkupAnnotation
```

Represents a text annotation that is a "sticky note" attached to a point in the PDF document.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextAnnotation(IDocument document)](#TextAnnotation-com.aspose.pdf.IDocument-) | Constructor for annotation when used in Generator. |
| [TextAnnotation(Page page, Rectangle rect)](#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new Text annotation on the specified page. |
| [TextAnnotation()](#TextAnnotation--) | Create TextAnnotation instance |
## Methods

| Method | Description |
| --- | --- |
| [getOpen()](#getOpen--) | Gets a flag specifying whether the annotation should initially be displayed open. |
| [setOpen(boolean value)](#setOpen-boolean-) | Sets a flag specifying whether the annotation should initially be displayed open. |
| [getIcon()](#getIcon--) | Gets an icon to be used in displaying the annotation. |
| [setIcon(int value)](#setIcon-int-) | Sets an icon to be used in displaying the annotation. |
| [getState()](#getState--) | Gets the state to which the original annotation should be set. |
| [setState(int value)](#setState-int-) | Sets the state to which the original annotation should be set. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [getStateModel()](#getStateModel--) | Gets state model |
| [changeAfterResize(Matrix transform)](#changeAfterResize-com.aspose.pdf.Matrix-) | Overrides the definition in the base class with an empty body. |
### TextAnnotation(IDocument document) {#TextAnnotation-com.aspose.pdf.IDocument-}
```
public TextAnnotation(IDocument document)
```


Constructor for annotation when used in Generator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Document where text annotation will be created. |

### TextAnnotation(Page page, Rectangle rect) {#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public TextAnnotation(Page page, Rectangle rect)
```


Creates new Text annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The annotation rectangle, defining the location of the annotation on the page. |

### TextAnnotation() {#TextAnnotation--}
```
public TextAnnotation()
```


Create TextAnnotation instance

### getOpen() {#getOpen--}
```
public boolean getOpen()
```


Gets a flag specifying whether the annotation should initially be displayed open.

**Returns:**
boolean - boolean value
### setOpen(boolean value) {#setOpen-boolean-}
```
public void setOpen(boolean value)
```


Sets a flag specifying whether the annotation should initially be displayed open.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getIcon() {#getIcon--}
```
public int getIcon()
```


Gets an icon to be used in displaying the annotation.

**Returns:**
int - TextIcon value
### setIcon(int value) {#setIcon-int-}
```
public void setIcon(int value)
```


Sets an icon to be used in displaying the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | TextIcon value |

### getState() {#getState--}
```
public int getState()
```


Gets the state to which the original annotation should be set.

**Returns:**
int - AnnotationState value
### setState(int value) {#setState-int-}
```
public void setState(int value)
```


Sets the state to which the original annotation should be set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | AnnotationState value |

### getAnnotationType() {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```


Gets type of annotation.

**Returns:**
[AnnotationType](../../com.aspose.pdf/annotationtype) - AnnotationType value
### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor object to process the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

### getStateModel() {#getStateModel--}
```
public AnnotationStateModel getStateModel()
```


Gets state model

**Returns:**
[AnnotationStateModel](../../com.aspose.pdf/annotationstatemodel) - AnnotationStateModel value
### changeAfterResize(Matrix transform) {#changeAfterResize-com.aspose.pdf.Matrix-}
```
public void changeAfterResize(Matrix transform)
```


Overrides the definition in the base class with an empty body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.pdf/matrix) | Matrix specifying the transformation. |

