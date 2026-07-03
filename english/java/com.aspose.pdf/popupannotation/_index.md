---
title: PopupAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents the pop-up annotation that displays text in a pop-up window for entry and editing.
type: docs
weight: 3930
url: /java/com.aspose.pdf/popupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PopupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PopupAnnotation extends Annotation
```

Represents the pop-up annotation that displays text in a pop-up window for entry and editing.

## Constructors

| Constructor | Description |
| --- | --- |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.IDocument-) | Constructor. for using in Generator. |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Creates new Popup annotation on the specified page. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [getAnnotationType](#getAnnotationType--) | Gets type of annotation. |
| [getOpen](#getOpen--) | Gets a flag specifying whether the pop-up annotation should initially be displayed open. |
| [getParent](#getParent--) | Gets the parent annotation with which this pop-up annotation shall be associated. If this entry is present, the parent annotation's Contents, M, C, and T entries shall override those of the pop-up annotation itself. |
| [setOpen](#setOpen-boolean-) | Sets a flag specifying whether the pop-up annotation should initially be displayed open. |
| [setParent](#setParent-com.aspose.pdf.MarkupAnnotation-) | Sets the parent annotation with which this pop-up annotation shall be associated. If this entry is present, the parent annotation's Contents, M, C, and T entries shall override those of the pop-up annotation itself. |

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.IDocument-}
Constructor. for using in Generator.

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Creates new Popup annotation on the specified page.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepts visitor object to process the annotation.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Gets type of annotation.

**Returns:**
AnnotationType element @see AnnotationType

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Gets a flag specifying whether the pop-up annotation should initially be displayed open.

**Returns:**
boolean value

### getParent {#getParent--}
```
public Annotation getParent()
```

Gets the parent annotation with which this pop-up annotation shall be associated. If this entry is present, the parent annotation's Contents, M, C, and T entries shall override those of the pop-up annotation itself.

**Returns:**
MarkupAnnotation object

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Sets a flag specifying whether the pop-up annotation should initially be displayed open.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setParent {#setParent-com.aspose.pdf.MarkupAnnotation-}
Sets the parent annotation with which this pop-up annotation shall be associated. If this entry is present, the parent annotation's Contents, M, C, and T entries shall override those of the pop-up annotation itself.
