---
title: "LinkAnnotation"
linktitle: "LinkAnnotation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل إما رابطًا تشعبيًا إلى وجهة أخرى في المستند أو إجراءً يجب تنفيذه."
type: docs
weight: 2760
url: /ar/java/com.aspose.pdf/linkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.LinkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class LinkAnnotation extends Annotation
```

يمثل إما رابطًا تشعبيًا إلى وجهة أخرى في المستند أو إجراءً يجب تنفيذه.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [LinkAnnotation](#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | ينشئ تعليقة رابط جديدة على الصفحة المحددة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | يقبل كائن الزائر لمعالجة التعليق. |
| [getAction](#getAction--) | احصل على الإجراء الذي سيُنفذ عندما يتم تنشيط تعليقة الرابط. |
| [getAnnotationType](#getAnnotationType--) | يحصل على نوع التعليق التوضيحي. |
| [getDestination](#getDestination--) | احصل على الوجهة التي ستُعرض عندما يتم تنشيط التعليقة. |
| [getHighlighting](#getHighlighting--) | احصل على التأثير البصري الذي سيُستخدم عندما يتم ضغط زر الفأرة أو الإبقاء عليه مضغوطًا داخل المنطقة النشطة. |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | اضبط الإجراء الذي سيُنفذ عندما يتم تنشيط تعليقة الرابط. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | اضبط الوجهة التي ستُعرض عندما يتم تنشيط التعليقة. |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | اضبط التأثير البصري الذي سيُستخدم عندما يتم ضغط زر الفأرة أو الإبقاء عليه مضغوطًا داخل المنطقة النشطة. |

### LinkAnnotation {#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
ينشئ تعليقة رابط جديدة على الصفحة المحددة.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
يقبل كائن الزائر لمعالجة التعليق.

### getAction {#getAction--}
```
public PdfAction getAction()
```

احصل على الإجراء الذي سيُنفذ عندما يتم تنشيط تعليقة الرابط.

**Returns:**
قيمة PdfAction

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

يحصل على نوع التعليق التوضيحي.

**Returns:**
عنصر AnnotationType @see AnnotationType

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

احصل على الوجهة التي ستُعرض عندما يتم تنشيط التعليقة.

**Returns:**
قيمة IAppointment

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

احصل على التأثير البصري الذي سيُستخدم عندما يتم ضغط زر الفأرة أو الإبقاء عليه مضغوطًا داخل المنطقة النشطة.

**Returns:**
عنصر HighlightingMode @see HighlightingMode

### setAction {#setAction-com.aspose.pdf.PdfAction-}
اضبط الإجراء الذي سيُنفذ عندما يتم تنشيط تعليقة الرابط.

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
اضبط الوجهة التي ستُعرض عندما يتم تنشيط التعليقة.

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
اضبط التأثير البصري الذي سيُستخدم عندما يتم ضغط زر الفأرة أو الإبقاء عليه مضغوطًا داخل المنطقة النشطة.
