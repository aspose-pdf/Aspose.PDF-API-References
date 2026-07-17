---
title: WidgetAnnotation
linktitle: WidgetAnnotation
second_title: Aspose.PDF for Java API Reference
description: Class representing widget annotation.
type: docs
weight: 5540
url: /java/com.aspose.pdf/widgetannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class WidgetAnnotation extends Annotation
```

Class representing widget annotation.

## Constructors

| Constructor | Description |
| --- | --- |
| [WidgetAnnotation](#WidgetAnnotation-com.aspose.pdf.IDocument-) | Create annotation (used for Generator) |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepts visitor. |
| [getAnnotationActions](#getAnnotationActions--) | Gets the annotation actions. |
| [getAnnotationType](#getAnnotationType--) | Gets type of annotation. |
| [getCheckedStateName](#getCheckedStateName--) | Returns name of "checked" state according to existing state names. |
| [getDefaultAppearance](#getDefaultAppearance--) | Gets default appearance of the field. |
| [getExportable](#getExportable--) | Gets exportable flag of the field. |
| [getHighlighting](#getHighlighting--) | Annotation highlighting mode. |
| [getOnActivated](#getOnActivated--) | Get an action which shall be performed when the annotation is activated. |
| [getParent](#getParent--) | Gets annotation parent. |
| [getReadOnly](#getReadOnly--) | Gets read only status of the field. |
| [getRequired](#getRequired--) | Gets required status of the field. |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Sets default appearance of the field. |
| [setExportable](#setExportable-boolean-) | Sets read only status of the field. |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | Annotation highlighting mode. |
| [setOnActivated](#setOnActivated-com.aspose.pdf.PdfAction-) | Set an action which shall be performed when the annotation is activated. |
| [setReadOnly](#setReadOnly-boolean-) | Sets read only status of the field. |
| [setRequired](#setRequired-boolean-) | Sets read only status of the field. |

### WidgetAnnotation {#WidgetAnnotation-com.aspose.pdf.IDocument-}
Create annotation (used for Generator)

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepts visitor.

### getAnnotationActions {#getAnnotationActions--}
```
public AnnotationActionCollection getAnnotationActions()
```

Gets the annotation actions.

**Returns:**
AnnotationActionCollection object

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Gets type of annotation.

**Returns:**
AnnotationType element @see AnnotationType

### getCheckedStateName {#getCheckedStateName--}
```
public final String getCheckedStateName()
```

Returns name of "checked" state according to existing state names.

**Returns:**
The name of the "checked" state for this annotation.

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

Gets default appearance of the field.

**Returns:**
DefaultAppearance object

### getExportable {#getExportable--}
```
public boolean getExportable()
```

Gets exportable flag of the field.

**Returns:**
boolean value

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

Annotation highlighting mode.

**Returns:**
HighlightingMode value @see HighlightingMode

### getOnActivated {#getOnActivated--}
```
public PdfAction getOnActivated()
```

Get an action which shall be performed when the annotation is activated.

**Returns:**
PdfAction object

### getParent {#getParent--}
```
public Field getParent()
```

Gets annotation parent.

**Returns:**
Field object

### getReadOnly {#getReadOnly--}
```
public boolean getReadOnly()
```

Gets read only status of the field.

**Returns:**
boolean value

### getRequired {#getRequired--}
```
public boolean getRequired()
```

Gets required status of the field.

**Returns:**
boolean value

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
Sets default appearance of the field.

### setExportable {#setExportable-boolean-}
```
public void setExportable(boolean value)
```

Sets read only status of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
Annotation highlighting mode.

### setOnActivated {#setOnActivated-com.aspose.pdf.PdfAction-}
Set an action which shall be performed when the annotation is activated.

### setReadOnly {#setReadOnly-boolean-}
```
public void setReadOnly(boolean value)
```

Sets read only status of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setRequired {#setRequired-boolean-}
```
public void setRequired(boolean value)
```

Sets read only status of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
