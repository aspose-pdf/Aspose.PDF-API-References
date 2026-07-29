---
title: "TextAnnotation"
linktitle: "TextAnnotation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل تعليقا نصيًا هو \\\"ملاحظة لاصقة\\\" مرفقة بنقطة في مستند PDF."
type: docs
weight: 4920
url: /ar/java/com.aspose.pdf/textannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class TextAnnotation extends MarkupAnnotation
```

يمثل تعليقا نصيًا هو "ملاحظة لاصقة" مرفقة بنقطة في مستند PDF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextAnnotation](#TextAnnotation--) | إنشاء مثيل TextAnnotation |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.IDocument-) | إنشاء مثيل TextAnnotation |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | إنشاء مثيل TextAnnotation |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | يقبل كائن الزائر لمعالجة التعليق. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | يتجاوز التعريف في الفئة الأساسية بجسم فارغ. |
| [getAnnotationType](#getAnnotationType--) | يحصل على نوع التعليق التوضيحي. |
| [getIcon](#getIcon--) | يحصل على أيقونة تُستخدم في عرض التعليق. |
| [getOpen](#getOpen--) | يحصل على علم يحدد ما إذا كان يجب عرض التعليق مفتوحًا في البداية. |
| [setIcon](#setIcon-int-) | يضبط أيقونة تُستخدم في عرض التعليق. |
| [setOpen](#setOpen-boolean-) | يضبط علمًا يحدد ما إذا كان يجب عرض التعليق مفتوحًا في البداية. |

### TextAnnotation {#TextAnnotation--}
```
public TextAnnotation()
```

إنشاء مثيل TextAnnotation

### TextAnnotation {#TextAnnotation-com.aspose.pdf.IDocument-}
إنشاء مثيل TextAnnotation

### TextAnnotation {#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
إنشاء مثيل TextAnnotation

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
يقبل كائن الزائر لمعالجة التعليق.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
يتجاوز التعريف في الفئة الأساسية بجسم فارغ.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

يحصل على نوع التعليق التوضيحي.

**Returns:**
قيمة AnnotationType @see AnnotationState

### getIcon {#getIcon--}
```
public int getIcon()
```

يحصل على أيقونة تُستخدم في عرض التعليق.

**Returns:**
قيمة TextIcon @see TextIcon

### getOpen {#getOpen--}
```
public boolean getOpen()
```

يحصل على علم يحدد ما إذا كان يجب عرض التعليق مفتوحًا في البداية.

**Returns:**
قيمة منطقية

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

يضبط أيقونة تُستخدم في عرض التعليق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة TextIcon @see TextIcon |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

يضبط علمًا يحدد ما إذا كان يجب عرض التعليق مفتوحًا في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
