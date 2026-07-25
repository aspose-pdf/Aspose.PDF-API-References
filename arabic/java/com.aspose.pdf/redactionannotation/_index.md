---
title: "RedactionAnnotation"
linktitle: "RedactionAnnotation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل تعليقة Redact."
type: docs
weight: 4120
url: /ar/java/com.aspose.pdf/redactionannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.RedactionAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class RedactionAnnotation extends MarkupAnnotation
```

يمثل تعليقة Redact.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.IDocument-) | منشئ لـ RedactionAnnotation. للاستخدام في Generator. |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | منشئ لـ RedactAnnotation. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | يقبل كائن الزائر لمعالجة التعليق. |
| [flatten](#flatten--) | يقوم بتسوية التعليقة أي يزيل التعليقة ويضيف محتواها |
| [getAnnotationType](#getAnnotationType--) | يحصل على نوع التعليق التوضيحي. |
| [getBorderColor](#getBorderColor--) | يحصل على لون الحدود التي تُرسم عندما لا تكون عملية الحذف نشطة. |
| [getDefaultAppearance](#getDefaultAppearance--) | يحصل أو يعيّن سلسلة المظهر الافتراضية التي تُستخدم في تنسيق النص. |
| [getFillColor](#getFillColor--) | يحصل على لون تعبئة التعليقة. |
| [getFontSize](#getFontSize--) | يحصل على حجم الخط لنص OverlayText. |
| [getOverlayText](#getOverlayText--) | يحصل على النص للطباعة على ملاحظة الحجب. |
| [getQuadPoint](#getQuadPoint--) | مصفوفة من الأعداد 8xN تحدد إحداثيات منطقة المحتوى التي يُقصد إزالتها. |
| [getQuadPoints](#getQuadPoints--) | يحصل على مصفوفة من النقاط التي تحدد إحداثيات n رباعيات. كل رباعية تشمل كلمة أو مجموعة من الكلمات المتجاورة في النص الأساسي للتعليق التوضيحي. |
| [getTextAlignment](#getTextAlignment--) | يحصل على محاذاة نص التراكب. |
| [isRepeat](#isRepeat--) | إذا كان صحيحًا، سيتكرر نص التراكب على الملاحظة. |
| [redact](#redact--) | يقوم بتسطيح الملاحظة ويُحجب محتويات الصفحة (أي يزيل النص ومحتوى الصورة تحت ملاحظة الحجب). |
| [redactExact](#redactExact--) | يقوم بتسطيح الملاحظة ويُحجب محتويات الصفحة (أي يزيل النص ومحتوى الصورة بدقة تحت ملاحظة الحجب). |
| [setBorderColor](#setBorderColor-com.aspose.pdf.Color-) | يضبط لون الإطار الذي يُرسم عندما لا يكون الحجب نشطًا. |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | يحصل أو يعيّن سلسلة المظهر الافتراضية التي تُستخدم في تنسيق النص. |
| [setFillColor](#setFillColor-com.aspose.pdf.Color-) | يضبط اللون لملء الملاحظة. |
| [setFontSize](#setFontSize-float-) | يضبط حجم الخط لنص التراكب. القيمة الافتراضية هي 10. |
| [setOverlayText](#setOverlayText-java.lang.String-) | يضبط النص للطباعة على ملاحظة الحجب. |
| [setQuadPoint](#setQuadPoint-com.aspose.pdf.Point:A-) | مصفوفة من الأعداد 8xN تحدد إحداثيات منطقة المحتوى التي يُقصد إزالتها. |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | يضبط مصفوفة من النقاط التي تحدد إحداثيات n رباعيات. كل رباعية تشمل كلمة أو مجموعة من الكلمات المتجاورة في النص الأساسي للتعليق التوضيحي. |
| [setRepeat](#setRepeat-boolean-) | إذا كان صحيحًا، سيتكرر نص التراكب على الملاحظة. |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | يضبط محاذاة نص التراكب. |

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.IDocument-}
منشئ لـ RedactionAnnotation. للاستخدام في Generator.

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
منشئ لـ RedactAnnotation.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
يقبل كائن الزائر لمعالجة التعليق.

### flatten {#flatten--}
```
public void flatten()
```

يقوم بتسوية التعليقة أي يزيل التعليقة ويضيف محتواها

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

يحصل على نوع التعليق التوضيحي.

**Returns:**
عنصر AnnotationType @see AnnotationType

### getBorderColor {#getBorderColor--}
```
public Color getBorderColor()
```

يحصل على لون الحدود التي تُرسم عندما لا تكون عملية الحذف نشطة.

**Returns:**
قيمة اللون

### getDefaultAppearance {#getDefaultAppearance--}
```
public final String getDefaultAppearance()
```

يحصل أو يعيّن سلسلة المظهر الافتراضية التي تُستخدم في تنسيق النص.

**Returns:**
قيمة سلسلة

### getFillColor {#getFillColor--}
```
public Color getFillColor()
```

يحصل على لون تعبئة التعليقة.

**Returns:**
قيمة اللون

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

يحصل على حجم الخط لنص OverlayText.

**Returns:**
قيمة int

### getOverlayText {#getOverlayText--}
```
public String getOverlayText()
```

يحصل على النص للطباعة على ملاحظة الحجب.

**Returns:**
قيمة السلسلة

### getQuadPoint {#getQuadPoint--}
```
public Point [] getQuadPoint()
```

مصفوفة من الأعداد 8xN تحدد إحداثيات منطقة المحتوى التي يُقصد إزالتها.

**Returns:**
مصفوفة من النقاط

### getQuadPoints {#getQuadPoints--}
```
@Deprecated public Point [] getQuadPoints()
```

يحصل على مصفوفة من النقاط التي تحدد إحداثيات n رباعيات. كل رباعية تشمل كلمة أو مجموعة من الكلمات المتجاورة في النص الأساسي للتعليق التوضيحي.

**Returns:**
مصفوفة من قيم Point

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

يحصل على محاذاة نص التراكب.

**Returns:**
قيمة HorizontalAlignment @see HorizontalAlignment

### isRepeat {#isRepeat--}
```
public boolean isRepeat()
```

إذا كان صحيحًا، سيتكرر نص التراكب على الملاحظة.

**Returns:**
قيمة منطقية

### redact {#redact--}
```
public void redact()
```

يقوم بتسطيح الملاحظة ويُحجب محتويات الصفحة (أي يزيل النص ومحتوى الصورة تحت ملاحظة الحجب).

### redactExact {#redactExact--}
```
public void redactExact()
```

يقوم بتسطيح الملاحظة ويُحجب محتويات الصفحة (أي يزيل النص ومحتوى الصورة بدقة تحت ملاحظة الحجب).

### setBorderColor {#setBorderColor-com.aspose.pdf.Color-}
يضبط لون الإطار الذي يُرسم عندما لا يكون الحجب نشطًا.

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
يحصل أو يعيّن سلسلة المظهر الافتراضية التي تُستخدم في تنسيق النص.

### setFillColor {#setFillColor-com.aspose.pdf.Color-}
يضبط اللون لملء الملاحظة.

### setFontSize {#setFontSize-float-}
```
public final void setFontSize(float fontSize)
```

يضبط حجم الخط لنص التراكب. القيمة الافتراضية هي 10.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontSize |  | قيمة int |

### setOverlayText {#setOverlayText-java.lang.String-}
يضبط النص للطباعة على ملاحظة الحجب.

### setQuadPoint {#setQuadPoint-com.aspose.pdf.Point:A-}
مصفوفة من الأعداد 8xN تحدد إحداثيات منطقة المحتوى التي يُقصد إزالتها.

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
يضبط مصفوفة من النقاط التي تحدد إحداثيات n رباعيات. كل رباعية تشمل كلمة أو مجموعة من الكلمات المتجاورة في النص الأساسي للتعليق التوضيحي.

### setRepeat {#setRepeat-boolean-}
```
public void setRepeat(boolean value)
```

إذا كان صحيحًا، سيتكرر نص التراكب على الملاحظة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
يضبط محاذاة نص التراكب.
