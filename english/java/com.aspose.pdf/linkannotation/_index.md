---
title: LinkAnnotation
linktitle: LinkAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents either a hypertext link to a destination elsewhere in the document or an action to be performed.
type: docs
weight: 2760
url: /java/com.aspose.pdf/linkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.LinkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class LinkAnnotation extends Annotation
```

Represents either a hypertext link to a destination elsewhere in the document or an action to be performed.

## Constructors

| Constructor | Description |
| --- | --- |
| [LinkAnnotation](#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new Link annotation on the specified page. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [getAction](#getAction--) | Get an action to be performed when the link annotation is activated. |
| [getAnnotationType](#getAnnotationType--) | Gets type of annotation. |
| [getDestination](#getDestination--) | Get a destination to be displayed when the annotation is activated. |
| [getHighlighting](#getHighlighting--) | Get the visual effect to be used when the mouse button is pressed or held down inside its active area. |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | Set an action to be performed when the link annotation is activated. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | Set a destination to be displayed when the annotation is activated. |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | Set the visual effect to be used when the mouse button is pressed or held down inside its active area. |

### LinkAnnotation {#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Creates new Link annotation on the specified page.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepts visitor object to process the annotation.

### getAction {#getAction--}
```
public PdfAction getAction()
```

Get an action to be performed when the link annotation is activated.

**Returns:**
PdfAction value

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Gets type of annotation.

**Returns:**
AnnotationType element @see AnnotationType

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

Get a destination to be displayed when the annotation is activated.

**Returns:**
IAppointment value

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

Get the visual effect to be used when the mouse button is pressed or held down inside its active area.

**Returns:**
HighlightingMode element @see HighlightingMode

### setAction {#setAction-com.aspose.pdf.PdfAction-}
Set an action to be performed when the link annotation is activated.

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
Set a destination to be displayed when the annotation is activated.

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
Set the visual effect to be used when the mouse button is pressed or held down inside its active area.
