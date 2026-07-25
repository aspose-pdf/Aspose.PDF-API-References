---
title: "PopupAnnotation"
linktitle: "PopupAnnotation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل تعليق المنبثقة الذي يعرض النص في نافذة منبثقة للإدخال والتحرير."
type: docs
weight: 3930
url: /ar/java/com.aspose.pdf/popupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PopupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PopupAnnotation extends Annotation
```

يمثل تعليق المنبثقة الذي يعرض النص في نافذة منبثقة للإدخال والتحرير.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.IDocument-) | منشئ. للاستخدام في Generator. |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | ينشئ تعليقا من Popup جديد على الصفحة المحددة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | يقبل كائن الزائر لمعالجة التعليق. |
| [getAnnotationType](#getAnnotationType--) | يحصل على نوع التعليق التوضيحي. |
| [getOpen](#getOpen--) | يحصل على علم يحدد ما إذا كان يجب عرض التعليق المنبثق مفتوحًا في البداية. |
| [getParent](#getParent--) | يحصل على التعليق الأب الذي يجب ربط هذا التعليق المنبثق به. إذا كان هذا الإدخال موجودًا، فإن حقول Contents و M و C و T في التعليق الأب ستحل محل ما في التعليق المنبثق نفسه. |
| [setOpen](#setOpen-boolean-) | يضبط علمًا يحدد ما إذا كان يجب عرض التعليق المنبثق مفتوحًا في البداية. |
| [setParent](#setParent-com.aspose.pdf.MarkupAnnotation-) | يضبط التعليق الأب الذي يجب ربط هذا التعليق المنبثق به. إذا كان هذا الإدخال موجودًا، فإن حقول Contents و M و C و T في التعليق الأب ستحل محل ما في التعليق المنبثق نفسه. |

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.IDocument-}
منشئ. للاستخدام في Generator.

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
ينشئ تعليقا من Popup جديد على الصفحة المحددة.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
يقبل كائن الزائر لمعالجة التعليق.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

يحصل على نوع التعليق التوضيحي.

**Returns:**
عنصر AnnotationType @see AnnotationType

### getOpen {#getOpen--}
```
public boolean getOpen()
```

يحصل على علم يحدد ما إذا كان يجب عرض التعليق المنبثق مفتوحًا في البداية.

**Returns:**
قيمة منطقية

### getParent {#getParent--}
```
public Annotation getParent()
```

يحصل على التعليق الأب الذي يجب ربط هذا التعليق المنبثق به. إذا كان هذا الإدخال موجودًا، فإن حقول Contents و M و C و T في التعليق الأب ستحل محل ما في التعليق المنبثق نفسه.

**Returns:**
كائن MarkupAnnotation

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

يضبط علمًا يحدد ما إذا كان يجب عرض التعليق المنبثق مفتوحًا في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setParent {#setParent-com.aspose.pdf.MarkupAnnotation-}
يضبط التعليق الأب الذي يجب ربط هذا التعليق المنبثق به. إذا كان هذا الإدخال موجودًا، فإن حقول Contents و M و C و T في التعليق الأب ستحل محل ما في التعليق المنبثق نفسه.
