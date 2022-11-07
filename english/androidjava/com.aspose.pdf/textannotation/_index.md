---
title: TextAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents a text annotation that is a ufffdsticky noteufffd attached to a point in the PDF document.
type: docs
weight: 288
url: /java/com.aspose.pdf/textannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.MarkupAnnotation](../../com.aspose.pdf/markupannotation)
```
public final class TextAnnotation extends MarkupAnnotation
```

Represents a text annotation that is a \\ufffdsticky note\\ufffd attached to a point in the PDF document.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextAnnotation(Page page, Rectangle rect)](#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new Text annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [writeXfdf(System.Xml.XmlWriter writer)](#writeXfdf-com.aspose.ms.System.Xml.XmlWriter-) |  |
| [getOpen()](#getOpen--) | Gets a flag specifying whether the annotation should initially be displayed open. |
| [setOpen(boolean value)](#setOpen-boolean-) | Sets a flag specifying whether the annotation should initially be displayed open. |
| [getIcon()](#getIcon--) | Gets an icon to be used in displaying the annotation. |
| [setIcon(int value)](#setIcon-int-) | Sets an icon to be used in displaying the annotation. |
| [getState()](#getState--) | Gets the state to which the original annotation should be set. |
| [setState(int value)](#setState-int-) | Sets the state to which the original annotation should be set. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [getStateModel()](#getStateModel--) |  |
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

### writeXfdf(System.Xml.XmlWriter writer) {#writeXfdf-com.aspose.ms.System.Xml.XmlWriter-}
```
public void writeXfdf(System.Xml.XmlWriter writer)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| writer | com.aspose.ms.System.Xml.XmlWriter |  |

### getOpen() {#getOpen--}
```
public boolean getOpen()
```


Gets a flag specifying whether the annotation should initially be displayed open.

**Returns:**
boolean
### setOpen(boolean value) {#setOpen-boolean-}
```
public void setOpen(boolean value)
```


Sets a flag specifying whether the annotation should initially be displayed open.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getIcon() {#getIcon--}
```
public int getIcon()
```


Gets an icon to be used in displaying the annotation.

**Returns:**
int
### setIcon(int value) {#setIcon-int-}
```
public void setIcon(int value)
```


Sets an icon to be used in displaying the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getState() {#getState--}
```
public int getState()
```


Gets the state to which the original annotation should be set.

**Returns:**
int
### setState(int value) {#setState-int-}
```
public void setState(int value)
```


Sets the state to which the original annotation should be set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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
public int getStateModel()
```




**Returns:**
int
