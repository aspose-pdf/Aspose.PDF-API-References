---
title: "CaretAnnotation"
linktitle: "CaretAnnotation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الفئة التي تمثل توضيح Caret."
type: docs
weight: 470
url: /ar/java/com.aspose.pdf/caretannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.CaretAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class CaretAnnotation extends MarkupAnnotation
```

الفئة التي تمثل توضيح Caret.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.IDocument-) | منشئ للاستخدام في Generator. |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | ينشئ تعليق Caret جديد على الصفحة المحددة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | يقبل كائن الزائر لمعالجة التعليق. |
| [getAnnotationType](#getAnnotationType--) | يحصل على نوع التعليق التوضيحي. |
| [getFrame](#getFrame--) | يحصل على مستطيل caret. |
| [getSymbol](#getSymbol--) | يحصل على الرمز المرتبط بـ caret. {@code CaretSymbol} |
| [setFrame](#setFrame-com.aspose.pdf.Rectangle-) | يضبط مستطيل caret. |
| [setSymbol](#setSymbol-com.aspose.pdf.CaretSymbol-) | يضبط حجم صفحة الإخراج للاستيراد. |

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.IDocument-}
منشئ للاستخدام في Generator.

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
ينشئ تعليق Caret جديد على الصفحة المحددة.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
يقبل كائن الزائر لمعالجة التعليق.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

يحصل على نوع التعليق التوضيحي.

**Returns:**
عنصر AnnotationType

### getFrame {#getFrame--}
```
public Rectangle getFrame()
```

يحصل على مستطيل caret.

**Returns:**
مستطيل caret.

### getSymbol {#getSymbol--}
```
public CaretSymbol getSymbol()
```

يحصل على الرمز المرتبط بـ caret. {@code CaretSymbol}

**Returns:**
عنصر CaretSymbol @see CaretSymbol

### setFrame {#setFrame-com.aspose.pdf.Rectangle-}
يضبط مستطيل caret.

### setSymbol {#setSymbol-com.aspose.pdf.CaretSymbol-}
يضبط حجم صفحة الإخراج للاستيراد.
