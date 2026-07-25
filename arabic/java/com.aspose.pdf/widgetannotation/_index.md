---
title: "WidgetAnnotation"
linktitle: "WidgetAnnotation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الفئة التي تمثل توضيح الودجت."
type: docs
weight: 5540
url: /ar/java/com.aspose.pdf/widgetannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class WidgetAnnotation extends Annotation
```

الفئة التي تمثل توضيح الودجت.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [WidgetAnnotation](#WidgetAnnotation-com.aspose.pdf.IDocument-) | إنشاء التعليق (مستخدم لـ Generator) |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | يقبل الزائر. |
| [getAnnotationActions](#getAnnotationActions--) | يحصل على إجراءات التعليق. |
| [getAnnotationType](#getAnnotationType--) | يحصل على نوع التعليق التوضيحي. |
| [getCheckedStateName](#getCheckedStateName--) | يرجع اسم الحالة "checked" وفقًا لأسماء الحالات الموجودة. |
| [getDefaultAppearance](#getDefaultAppearance--) | يحصل على المظهر الافتراضي للحقل. |
| [getExportable](#getExportable--) | يحصل على علامة التصدير للحقل. |
| [getHighlighting](#getHighlighting--) | وضع تمييز التعليق. |
| [getOnActivated](#getOnActivated--) | احصل على الإجراء الذي يجب تنفيذه عندما يتم تنشيط التعليق. |
| [getParent](#getParent--) | يحصل على أصل التعليق. |
| [getReadOnly](#getReadOnly--) | يحصل على حالة القراءة فقط للحقل. |
| [getRequired](#getRequired--) | يحصل على حالة الإلزامية للحقل. |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | يضبط المظهر الافتراضي للحقل. |
| [setExportable](#setExportable-boolean-) | يضبط حالة القراءة فقط للحقل. |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | وضع تمييز التعليق. |
| [setOnActivated](#setOnActivated-com.aspose.pdf.PdfAction-) | اضبط إجراءً يجب تنفيذه عندما يتم تنشيط التعليق. |
| [setReadOnly](#setReadOnly-boolean-) | يضبط حالة القراءة فقط للحقل. |
| [setRequired](#setRequired-boolean-) | يضبط حالة القراءة فقط للحقل. |

### WidgetAnnotation {#WidgetAnnotation-com.aspose.pdf.IDocument-}
إنشاء التعليق (مستخدم لـ Generator)

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
يقبل الزائر.

### getAnnotationActions {#getAnnotationActions--}
```
public AnnotationActionCollection getAnnotationActions()
```

يحصل على إجراءات التعليق.

**Returns:**
AnnotationActionCollection كائن

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

يحصل على نوع التعليق التوضيحي.

**Returns:**
عنصر AnnotationType @see AnnotationType

### getCheckedStateName {#getCheckedStateName--}
```
public final String getCheckedStateName()
```

يرجع اسم الحالة "checked" وفقًا لأسماء الحالات الموجودة.

**Returns:**
اسم الحالة "checked" لهذا التعليق.

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

يحصل على المظهر الافتراضي للحقل.

**Returns:**
كائن DefaultAppearance

### getExportable {#getExportable--}
```
public boolean getExportable()
```

يحصل على علامة التصدير للحقل.

**Returns:**
قيمة منطقية

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

وضع تمييز التعليق.

**Returns:**
HighlightingMode قيمة @see HighlightingMode

### getOnActivated {#getOnActivated--}
```
public PdfAction getOnActivated()
```

احصل على الإجراء الذي يجب تنفيذه عندما يتم تنشيط التعليق.

**Returns:**
كائن PdfAction

### getParent {#getParent--}
```
public Field getParent()
```

يحصل على أصل التعليق.

**Returns:**
Field كائن

### getReadOnly {#getReadOnly--}
```
public boolean getReadOnly()
```

يحصل على حالة القراءة فقط للحقل.

**Returns:**
قيمة منطقية

### getRequired {#getRequired--}
```
public boolean getRequired()
```

يحصل على حالة الإلزامية للحقل.

**Returns:**
قيمة منطقية

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
يضبط المظهر الافتراضي للحقل.

### setExportable {#setExportable-boolean-}
```
public void setExportable(boolean value)
```

يضبط حالة القراءة فقط للحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
وضع تمييز التعليق.

### setOnActivated {#setOnActivated-com.aspose.pdf.PdfAction-}
اضبط إجراءً يجب تنفيذه عندما يتم تنشيط التعليق.

### setReadOnly {#setReadOnly-boolean-}
```
public void setReadOnly(boolean value)
```

يضبط حالة القراءة فقط للحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setRequired {#setRequired-boolean-}
```
public void setRequired(boolean value)
```

يضبط حالة القراءة فقط للحقل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
