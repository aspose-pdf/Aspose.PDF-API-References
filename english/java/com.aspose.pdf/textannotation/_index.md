---
title: TextAnnotation
second_title: Aspose.PDF for Java API Reference
description: Represents a text annotation that is a \"sticky note\" attached to a point in the PDF document.
type: docs
weight: 4920
url: /java/com.aspose.pdf/textannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class TextAnnotation extends MarkupAnnotation
```

Represents a text annotation that is a "sticky note" attached to a point in the PDF document.

## Constructors

| Constructor | Description |
| --- | --- |
| [TextAnnotation](#TextAnnotation--) | Create TextAnnotation instance |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.IDocument-) | Create TextAnnotation instance |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Create TextAnnotation instance |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor object to process the annotation. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Overrides the definition in the base class with an empty body. |
| [getAnnotationType](#getAnnotationType--) | Gets type of annotation. |
| [getIcon](#getIcon--) | Gets an icon to be used in displaying the annotation. |
| [getOpen](#getOpen--) | Gets a flag specifying whether the annotation should initially be displayed open. |
| [setIcon](#setIcon-int-) | Sets an icon to be used in displaying the annotation. |
| [setOpen](#setOpen-boolean-) | Sets a flag specifying whether the annotation should initially be displayed open. |

### TextAnnotation {#TextAnnotation--}
```
public TextAnnotation()
```

Create TextAnnotation instance

### TextAnnotation {#TextAnnotation-com.aspose.pdf.IDocument-}
Create TextAnnotation instance

### TextAnnotation {#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Create TextAnnotation instance

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepts visitor object to process the annotation.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Overrides the definition in the base class with an empty body.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Gets type of annotation.

**Returns:**
AnnotationType value @see AnnotationState

### getIcon {#getIcon--}
```
public int getIcon()
```

Gets an icon to be used in displaying the annotation.

**Returns:**
TextIcon value @see TextIcon

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Gets a flag specifying whether the annotation should initially be displayed open.

**Returns:**
boolean value

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

Sets an icon to be used in displaying the annotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | TextIcon value @see TextIcon |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Sets a flag specifying whether the annotation should initially be displayed open.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
