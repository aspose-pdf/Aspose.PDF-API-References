---
title: "ScreenAnnotation"
linktitle: "ScreenAnnotation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "تعليق شاشة يحدد منطقة من الصفحة يمكن تشغيل مقاطع الوسائط فيها."
type: docs
weight: 4470
url: /ar/java/com.aspose.pdf/screenannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.ScreenAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.ScreenAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.ScreenAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class ScreenAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

تعليق شاشة يحدد منطقة من الصفحة يمكن تشغيل مقاطع الوسائط فيها.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ScreenAnnotation](#ScreenAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | إنشاء Screen annotation جديد على الصفحة المحددة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | تمثيل طريقة accept |
| [getAction](#getAction--) | يحصل على الإجراء الذي سيتم تنفيذه عندما يتم تنشيط annotation. |
| [getAnnotationType](#getAnnotationType--) | يحصل على نوع التعليق التوضيحي. |
| [getTitle](#getTitle--) | يحصل على عنوان screen annotation. |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | يضبط الإجراء الذي سيتم تنفيذه عندما يتم تنشيط annotation. |
| [setTitle](#setTitle-java.lang.String-) | يضبط عنوان screen annotation. |

### ScreenAnnotation {#ScreenAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
إنشاء Screen annotation جديد على الصفحة المحددة.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
تمثيل طريقة accept

### getAction {#getAction--}
```
public PdfAction getAction()
```

يحصل على الإجراء الذي سيتم تنفيذه عندما يتم تنشيط annotation.

**Returns:**
كائن PdfAction

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

يحصل على نوع التعليق التوضيحي.

**Returns:**
عنصر AnnotationType @see AnnotationType

### getTitle {#getTitle--}
```
public String getTitle()
```

يحصل على عنوان screen annotation.

**Returns:**
قيمة سلسلة

### setAction {#setAction-com.aspose.pdf.PdfAction-}
يضبط الإجراء الذي سيتم تنفيذه عندما يتم تنشيط annotation.

### setTitle {#setTitle-java.lang.String-}
يضبط عنوان screen annotation.
