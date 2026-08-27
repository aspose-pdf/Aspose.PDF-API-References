---
title: "FreeTextAnnotation"
linktitle: "FreeTextAnnotation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل تعليقا نصيا حرا يعرض النص مباشرة على الصفحة. على عكس التعليق النصي العادي، لا يمتلك التعليق النصي الحر حالة مفتوحة أو مغلقة؛ بدلاً من ذلك."
type: docs
weight: 1790
url: /ar/java/com.aspose.pdf/freetextannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.FreeTextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class FreeTextAnnotation extends MarkupAnnotation
```

يمثل تعليقة نص حر تعرض النص مباشرة على الصفحة. على عكس تعليقة النص العادية، لا تمتلك تعليقة النص الحر حالة فتح أو إغلاق؛ بدلاً من عرضها في نافذة منبثقة، يكون النص دائمًا مرئيًا.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-) | منشئ للاستخدام مع Generator. |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-) | ينشئ تعليقا نصيا حرا جديدًا على الصفحة المحددة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | يقبل كائن الزائر لمعالجة التعليق. |
| [getAnnotationType](#getAnnotationType--) | يحصل على نوع التعليق التوضيحي. |
| [getCallout](#getCallout--) | مصفوفة من النقاط تحدد خط الإشارة. |
| [getDefaultAppearance](#getDefaultAppearance--) | يحصل على سلسلة المظهر الافتراضي المستخدمة في تنسيق النص. |
| [getDefaultAppearanceObject](#getDefaultAppearanceObject--) | كائن يمثل المظهر الافتراضي لتعليق FreeText. |
| [getDefaultStyle](#getDefaultStyle--) | يحصل على سلسلة نمط افتراضية. |
| [getEndingStyle](#getEndingStyle--) | يحصل على نمط نهاية الخط لنقطة نهاية الخط. |
| [getIntent](#getIntent--) | يحصل على نية التعليق النصي الحر. |
| [getJustification](#getJustification--) | يحصل على رمز يحدد شكل التوزيع (المحاذاة) المستخدم في عرض نص التعليق. |
| [getRotate](#getRotate--) | زاوية دوران التعليق. |
| [getStartingStyle](#getStartingStyle--) | يحصل أو يضبط نمط نهاية الخط لنقطة نهاية الخط. هذه الخاصية قديمة، يرجى استخدام EndingStyle. |
| [getTextRectangle](#getTextRectangle--) | مستطيل يصف الفروق العددية بين مستطيلين: مدخل Rect للتعليق ومستطيل داخل ذلك المستطيل. المستطيل الداخلي هو المكان الذي يجب عرض نص التعليق فيه. |
| [getTextStyle](#getTextStyle--) | يحصل أو يضبط نمط النص في المظهر. عندما يتغير نمط النص، يتم تحديث مظهر النص. |
| [isValidXml](#isValidXml-java.lang.String-) |  |
| [setCallout](#setCallout-com.aspose.pdf.Point:A-) | مصفوفة من النقاط تحدد خط الإشارة. |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | يضبط سلسلة المظهر الافتراضي المستخدمة في تنسيق النص. |
| [setDefaultStyle](#setDefaultStyle-java.lang.String-) | يضبط سلسلة نمط افتراضية. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | يضبط نمط نهاية الخط لنقطة نهاية الخط. |
| [setIntent](#setIntent-com.aspose.pdf.FreeTextIntent-) | يضبط نية التعليق النصي الحر. |
| [setJustification](#setJustification-com.aspose.pdf.Justification-) | يضبط رمزًا يحدد شكل التوزيع (المحاذاة) المستخدم في عرض نص التعليق. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | زاوية دوران التعليق. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | يحصل أو يضبط نمط نهاية الخط لنقطة نهاية الخط. هذه الخاصية قديمة، يرجى استخدام EndingStyle. |
| [setTextRectangle](#setTextRectangle-com.aspose.pdf.Rectangle-) | مستطيل يصف الفروق العددية بين مستطيلين: مدخل Rect للتعليق ومستطيل داخل ذلك المستطيل. المستطيل الداخلي هو المكان الذي يجب عرض نص التعليق فيه. |
| [setTextStyle](#setTextStyle-int-int-int-) | يضبط التنسيق المحدد بواسطة المعامل textStyle لجزء نص من الفهرس fromInd إلى الفهرس toInd. |
| [setTextStyle](#setTextStyle-int-java.lang.String-double-java.awt.Color-) | يضبط التنسيق المحدد بواسطة المعامل textStyle لجميع نصوص التعليقات التوضيحية. |
| [setTextStyle](#setTextStyle-com.aspose.pdf.TextStyle-) | يضبط نمط النص في المظهر. عندما يتم تغيير نمط النص، يتم تحديث مظهر النص. |
| [updateAppearance](#updateAppearance--) | يقوم بتحديث المظهر بعد تغيير/نقل النص. |

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-}
منشئ للاستخدام مع Generator.

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-}
ينشئ تعليقا نصيا حرا جديدًا على الصفحة المحددة.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
يقبل كائن الزائر لمعالجة التعليق.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

يحصل على نوع التعليق التوضيحي.

**Returns:**
قيمة int

### getCallout {#getCallout--}
```
public final Point [] getCallout()
```

مصفوفة من النقاط تحدد خط الإشارة.

**Returns:**
مصفوفة من Point

### getDefaultAppearance {#getDefaultAppearance--}
```
public String getDefaultAppearance()
```

يحصل على سلسلة المظهر الافتراضي المستخدمة في تنسيق النص.

**Returns:**
قيمة سلسلة

### getDefaultAppearanceObject {#getDefaultAppearanceObject--}
```
public final DefaultAppearance getDefaultAppearanceObject()
```

كائن يمثل المظهر الافتراضي لتعليق FreeText.

**Returns:**
كائن DefaultAppearance

### getDefaultStyle {#getDefaultStyle--}
```
public String getDefaultStyle()
```

يحصل على سلسلة نمط افتراضية.

**Returns:**
قيمة سلسلة

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

يحصل على نمط نهاية الخط لنقطة نهاية الخط.

**Returns:**
قيمة LineEnding @see LineEnding

### getIntent {#getIntent--}
```
public FreeTextIntent getIntent()
```

يحصل على نية التعليق النصي الحر.

**Returns:**
قيمة int @see FreeTextIntent

### getJustification {#getJustification--}
```
public Justification getJustification()
```

يحصل على رمز يحدد شكل التوزيع (المحاذاة) المستخدم في عرض نص التعليق.

**Returns:**
قيمة int @see Justification

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

زاوية دوران التعليق.

**Returns:**
عنصر Rotation @see Rotation

### getStartingStyle {#getStartingStyle--}
```
public final LineEnding getStartingStyle()
```

يحصل أو يضبط نمط نهاية الخط لنقطة نهاية الخط. هذه الخاصية قديمة، يرجى استخدام EndingStyle.

**Returns:**
عنصر LineEnding

### getTextRectangle {#getTextRectangle--}
```
public final Rectangle getTextRectangle()
```

مستطيل يصف الفروق العددية بين مستطيلين: مدخل Rect للتعليق ومستطيل داخل ذلك المستطيل. المستطيل الداخلي هو المكان الذي يجب عرض نص التعليق فيه.

**Returns:**
مثيل Rectangle

### getTextStyle {#getTextStyle--}
```
public TextStyle getTextStyle()
```

يحصل أو يضبط نمط النص في المظهر. عندما يتغير نمط النص، يتم تحديث مظهر النص.

**Returns:**
قيمة TextStyle

### isValidXml {#isValidXml-java.lang.String-}


### setCallout {#setCallout-com.aspose.pdf.Point:A-}
مصفوفة من النقاط تحدد خط الإشارة.

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
يضبط سلسلة المظهر الافتراضي المستخدمة في تنسيق النص.

### setDefaultStyle {#setDefaultStyle-java.lang.String-}
يضبط سلسلة نمط افتراضية.

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
يضبط نمط نهاية الخط لنقطة نهاية الخط.

### setIntent {#setIntent-com.aspose.pdf.FreeTextIntent-}
يضبط نية التعليق النصي الحر.

### setJustification {#setJustification-com.aspose.pdf.Justification-}
يضبط رمزًا يحدد شكل التوزيع (المحاذاة) المستخدم في عرض نص التعليق.

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
زاوية دوران التعليق.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
يحصل أو يضبط نمط نهاية الخط لنقطة نهاية الخط. هذه الخاصية قديمة، يرجى استخدام EndingStyle.

### setTextRectangle {#setTextRectangle-com.aspose.pdf.Rectangle-}
مستطيل يصف الفروق العددية بين مستطيلين: مدخل Rect للتعليق ومستطيل داخل ذلك المستطيل. المستطيل الداخلي هو المكان الذي يجب عرض نص التعليق فيه.

### setTextStyle {#setTextStyle-int-int-int-}
```
public final void setTextStyle(int fromInd, int toInd, int textStyles)
```

يضبط التنسيق المحدد بواسطة المعامل textStyle لجزء نص من الفهرس fromInd إلى الفهرس toInd.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fromInd |  | الفهرس الابتدائي لجزء النص (بدءًا من 0). |
| toInd |  | الفهرس النهائي لجزء النص (يُحسب من 0، ولا يُضمّن هذا الفهرس). |
| textStyles |  | النمط(ات) المطبقة على جزء النص. |

### setTextStyle {#setTextStyle-int-java.lang.String-double-java.awt.Color-}
يضبط التنسيق المحدد بواسطة المعامل textStyle لجميع نصوص التعليقات التوضيحية.

### setTextStyle {#setTextStyle-com.aspose.pdf.TextStyle-}
يضبط نمط النص في المظهر. عندما يتم تغيير نمط النص، يتم تحديث مظهر النص.

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

يقوم بتحديث المظهر بعد تغيير/نقل النص.
