---
title: LinkAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents either a hypertext link to a destination elsewhere in the document or an action to be performed.
type: docs
weight: 203
url: /java/com.aspose.pdf/linkannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation)
```
public final class LinkAnnotation extends Annotation
```

Represents either a hypertext link to a destination elsewhere in the document or an action to be performed.
## Constructors

| Constructor | Description |
| --- | --- |
| [LinkAnnotation(Page page, Rectangle rect)](#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new Link annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [getAction()](#getAction--) | Get an action to be performed when the link annotation is activated. |
| [setAction(PdfAction value)](#setAction-com.aspose.pdf.PdfAction-) | Set an action to be performed when the link annotation is activated. |
| [getDestination()](#getDestination--) | Get a destination to be displayed when the annotation is activated. |
| [setDestination(IAppointment value)](#setDestination-com.aspose.pdf.IAppointment-) | Set a destination to be displayed when the annotation is activated. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [getHighlighting()](#getHighlighting--) | Get the visual effect to be used when the mouse button is pressed or held down inside its active area. |
| [setHighlighting(int value)](#setHighlighting-int-) | Set the visual effect to be used when the mouse button is pressed or held down inside its active area. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
### LinkAnnotation(Page page, Rectangle rect) {#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public LinkAnnotation(Page page, Rectangle rect)
```


Creates new Link annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The annotation rectangle, defining the location of the annotation on the page. |

### getAction() {#getAction--}
```
public PdfAction getAction()
```


Get an action to be performed when the link annotation is activated.

**Returns:**
[PdfAction](../../com.aspose.pdf/pdfaction) - PdfAction value
### setAction(PdfAction value) {#setAction-com.aspose.pdf.PdfAction-}
```
public void setAction(PdfAction value)
```


Set an action to be performed when the link annotation is activated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction object |

### getDestination() {#getDestination--}
```
public IAppointment getDestination()
```


Get a destination to be displayed when the annotation is activated.

**Returns:**
[IAppointment](../../com.aspose.pdf/iappointment) - IAppointment value
### setDestination(IAppointment value) {#setDestination-com.aspose.pdf.IAppointment-}
```
public void setDestination(IAppointment value)
```


Set a destination to be displayed when the annotation is activated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAppointment](../../com.aspose.pdf/iappointment) | IAppointment object |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor object to process the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

### getHighlighting() {#getHighlighting--}
```
public int getHighlighting()
```


Get the visual effect to be used when the mouse button is pressed or held down inside its active area.

**Returns:**
int - HighlightingMode element
### setHighlighting(int value) {#setHighlighting-int-}
```
public void setHighlighting(int value)
```


Set the visual effect to be used when the mouse button is pressed or held down inside its active area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HighlightingMode element |

### getAnnotationType() {#getAnnotationType--}
```
public int getAnnotationType()
```


Gets type of annotation.

**Returns:**
int - AnnotationType element
