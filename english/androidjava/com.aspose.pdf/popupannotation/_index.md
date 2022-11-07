---
title: PopupAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents the pop-up annotation that displays text in a pop-up window for entry and editing.
type: docs
weight: 236
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
| [PopupAnnotation(Page page, Rectangle rect)](#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new Popup annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [writeXfdf(System.Xml.XmlWriter writer)](#writeXfdf-com.aspose.ms.System.Xml.XmlWriter-) |  |
| [getOpen()](#getOpen--) | Gets a flag specifying whether the pop-up annotation should initially be displayed open. |
| [setOpen(boolean value)](#setOpen-boolean-) | Sets a flag specifying whether the pop-up annotation should initially be displayed open. |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
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


Gets a flag specifying whether the pop-up annotation should initially be displayed open.

**Returns:**
boolean
### setOpen(boolean value) {#setOpen-boolean-}
```
public void setOpen(boolean value)
```


Sets a flag specifying whether the pop-up annotation should initially be displayed open.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Accepts visitor object to process the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | Visitor object. |

