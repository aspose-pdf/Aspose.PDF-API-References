---
title: ScreenAnnotation
linktitle: ScreenAnnotation
second_title: Aspose.PDF for Java API Reference
description: A screen annotation that specifies a region of a page upon which media clips may be played.
type: docs
weight: 4470
url: /java/com.aspose.pdf/screenannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.ScreenAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.ScreenAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.ScreenAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class ScreenAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

A screen annotation that specifies a region of a page upon which media clips may be played.

## Constructors

| Constructor | Description |
| --- | --- |
| [ScreenAnnotation](#ScreenAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Creates new Screen annotation on the specified page. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Represent accept method |
| [getAction](#getAction--) | Gets an action to be performed when the annotation is activated. |
| [getAnnotationType](#getAnnotationType--) | Gets type of annotation. |
| [getTitle](#getTitle--) | Gets the title of the screen annotation. |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | Sets an action to be performed when the annotation is activated. |
| [setTitle](#setTitle-java.lang.String-) | Sets the title of the screen annotation. |

### ScreenAnnotation {#ScreenAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Creates new Screen annotation on the specified page.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Represent accept method

### getAction {#getAction--}
```
public PdfAction getAction()
```

Gets an action to be performed when the annotation is activated.

**Returns:**
PdfAction object

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Gets type of annotation.

**Returns:**
AnnotationType element @see AnnotationType

### getTitle {#getTitle--}
```
public String getTitle()
```

Gets the title of the screen annotation.

**Returns:**
String value

### setAction {#setAction-com.aspose.pdf.PdfAction-}
Sets an action to be performed when the annotation is activated.

### setTitle {#setTitle-java.lang.String-}
Sets the title of the screen annotation.
