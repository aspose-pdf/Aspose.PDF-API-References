---
title: "InkAnnotation"
linktitle: "InkAnnotation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل \\\"scribble\\\" حر اليد مكوّن من مسار (مسارات) منفصلة واحدة أو أكثر."
type: docs
weight: 2430
url: /ar/java/com.aspose.pdf/inkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.InkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class InkAnnotation extends MarkupAnnotation
```

يمثل \"خربشة\" يدوية تتكون من مسار واحد أو أكثر غير متصل.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-) | منشئ لتعليق Ink للمولد. |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-) | ينشئ تعليق Ink جديد على الصفحة المحددة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | يقبل كائن الزائر لمعالجة التعليق. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | يحدّث النقاط في InkList وفقًا لتحويل المصفوفة. |
| [getAnnotationType](#getAnnotationType--) | يحصل على نوع التعليق التوضيحي. |
| [getCapStyle](#getCapStyle--) | احصل على نمط نهايات خطوط تعليق Ink. |
| [getInkList](#getInkList--) | <p> يحصل على قائمة الإيماءات التي هي خطوط مستقلة ممثلة بمصفوفات Point[] . </p> |
| [setCapStyle](#setCapStyle-com.aspose.pdf.CapStyle-) | تعيين نمط نهايات خطوط التعليق بالحبر. |
| [setInkList](#setInkList-java.util.List-) | يضبط قائمة الإيماءات التي هي خطوط مستقلة ممثلة بمصفوفات Point[]. |
| [updateAppearance](#updateAppearance--) | يقوم بتحديث المظهر بعد تغيير/نقل النص. |

### InkAnnotation {#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-}
منشئ لتعليق Ink للمولد.

### InkAnnotation {#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-}
ينشئ تعليق Ink جديد على الصفحة المحددة.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
يقبل كائن الزائر لمعالجة التعليق.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
يحدّث النقاط في InkList وفقًا لتحويل المصفوفة.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

يحصل على نوع التعليق التوضيحي.

**Returns:**
عنصر AnnotationType @see AnnotationType

### getCapStyle {#getCapStyle--}
```
public CapStyle getCapStyle()
```

احصل على نمط نهايات خطوط تعليق Ink.

**Returns:**
عنصر CapStyle @see CapStyle

### getInkList {#getInkList--}
```
public List < Point []> getInkList()
```

<p> يحصل على قائمة الإيماءات التي هي خطوط مستقلة ممثلة بمصفوفات Point[] . </p>

**Returns:**
كائن {@code List<Point[]>}

### setCapStyle {#setCapStyle-com.aspose.pdf.CapStyle-}
تعيين نمط نهايات خطوط التعليق بالحبر.

### setInkList {#setInkList-java.util.List-}
يضبط قائمة الإيماءات التي هي خطوط مستقلة ممثلة بمصفوفات Point[].

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

يقوم بتحديث المظهر بعد تغيير/نقل النص.
