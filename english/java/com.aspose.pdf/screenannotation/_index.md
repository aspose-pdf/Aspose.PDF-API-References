---
title: ScreenAnnotation
second_title: Aspose.PDF for Java API Reference
description: A screen annotation that specifies a region of a page upon which media clips may be played.
type: docs
weight: 325
url: /java/com.aspose.pdf/screenannotation/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation)

**All Implemented Interfaces:**
[com.aspose.pdf.engine.ITitledAnnotation](../../com.aspose.pdf.engine/ititledannotation)
```
public final class ScreenAnnotation extends Annotation implements ITitledAnnotation
```

A screen annotation that specifies a region of a page upon which media clips may be played.
## Constructors

| Constructor | Description |
| --- | --- |
| [ScreenAnnotation(Page page, Rectangle rect, String mediaFile)](#ScreenAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Creates new Screen annotation on the specified page. |
## Methods

| Method | Description |
| --- | --- |
| [accept(AnnotationSelector visitor)](#accept-com.aspose.pdf.AnnotationSelector-) | Represent accept method |
| [getTitle()](#getTitle--) | Gets the title of the screen annotation. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets the title of the screen annotation. |
| [getAction()](#getAction--) | Gets an action to be performed when the annotation is activated. |
| [setAction(PdfAction value)](#setAction-com.aspose.pdf.PdfAction-) | Sets an action to be performed when the annotation is activated. |
| [getAnnotationType()](#getAnnotationType--) | Gets type of annotation. |
### ScreenAnnotation(Page page, Rectangle rect, String mediaFile) {#ScreenAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
```
public ScreenAnnotation(Page page, Rectangle rect, String mediaFile)
```


Creates new Screen annotation on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The document's page where annotation should be created. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | The annotation rectangle, defining the location of the annotation on the page. |
| mediaFile | java.lang.String | The path to multimedia file. |

### accept(AnnotationSelector visitor) {#accept-com.aspose.pdf.AnnotationSelector-}
```
public void accept(AnnotationSelector visitor)
```


Represent accept method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [AnnotationSelector](../../com.aspose.pdf/annotationselector) | AnnotationSelector object |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Gets the title of the screen annotation.

**Returns:**
java.lang.String - String value
### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Sets the title of the screen annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getAction() {#getAction--}
```
public PdfAction getAction()
```


Gets an action to be performed when the annotation is activated.

**Returns:**
[PdfAction](../../com.aspose.pdf/pdfaction) - PdfAction object
### setAction(PdfAction value) {#setAction-com.aspose.pdf.PdfAction-}
```
public void setAction(PdfAction value)
```


Sets an action to be performed when the annotation is activated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction object |

### getAnnotationType() {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```


Gets type of annotation.

**Returns:**
[AnnotationType](../../com.aspose.pdf/annotationtype) - AnnotationType element
