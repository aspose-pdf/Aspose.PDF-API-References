---
title: "TextState"
linktitle: "TextState"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل حالة نصية لنص"
type: docs
weight: 5340
url: /ar/java/com.aspose.pdf/textstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState

```
public class TextState extends Object
```

يمثل حالة نصية لنص

## الحقول

| حقل | الوصف |
| --- | --- |
| [TabstopDefaultValue](#TabstopDefaultValue) | القيمة الافتراضية للجدولة في عرض حرف المسافة للخط الافتراضي. |

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextState](#TextState--) | ينشئ كائن حالة النص. |
| [TextState](#TextState-java.awt.Color-) | ينشئ كائن حالة النص. |
| [TextState](#TextState-java.awt.Color-double-) | ينشئ كائن حالة النص. |
| [TextState](#TextState-double-) | ينشئ كائن حالة النص مع تحديد حجم الخط. |
| [TextState](#TextState-java.lang.String-) | ينشئ كائن حالة النص. |
| [TextState](#TextState-java.lang.String-boolean-boolean-) | ينشئ كائن حالة النص. |
| [TextState](#TextState-java.lang.String-double-) | ينشئ كائن حالة النص. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> يطبّق الإعدادات من textState آخر </p> <hr> <p> سيتم نسخ الخصائص التي تم تغييرها صراحةً فقط. </p> |
| [calculateFontSize](#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-) | يحسب حجم الخط للمستطيل. |
| [getBackgroundColor](#getBackgroundColor--) | <p> يحصل على لون خلفية النص. </p> <hr> <p> لاحظ أن القيمة لا تُحفظ كخاصية نصية داخل المستند. يعمل مُستخرج الخاصية BackgroundColor لكائن في حال تم تعيينه صراحةً مسبقًا باستخدام مُعيّن BackgroundColor لذلك الكائن. تُستخدم الخاصية بواسطة وقت التشغيل في سياق عملية الإنشاء/التعديل الحالية. </p> |
| [getCharacterSpacing](#getCharacterSpacing--) | يحصل على تباعد الأحرف في النص. |
| [getCoordinateOrigin](#getCoordinateOrigin--) | يحصل أو يعيّن CoordinateOrigin للنص. إذا كان CoordinateOrigin هو Descender، فإن إحداثي Y للنص يتطابق مع أدنى نقطة للخط. إذا كان CoordinateOrigin هو BaseLine، فإن إحداثي Y للنص يتطابق مع خط الأساس للخط. القيمة الافتراضية هي Descender. إذا كانت قيمة Descent للخط كبيرة جدًا، قد يُظهر النص أعلى من الخطوط الأخرى. في هذه الحالة يمكن اختيار CoordinateOrigin BaseLine للحصول على عرض نص أفضل. |
| [getFont](#getFont--) | يحصل على خط النص. |
| [getfontSize](#getfontSize--) | يمثّل طريقة getfontSize |
| [getFontSize](#getFontSize--) | يحصل على حجم الخط للنص. |
| [getFontStyle](#getFontStyle--) | يضبط نمط الخط للنص. |
| [getForegroundColor](#getForegroundColor--) | يحصل على لون المقدمة للنص. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> يحصل على المحاذاة الأفقية للنص. </p> <hr> <p> HorizontalAlignment.None يساوي HorizontalAlignment.Left. لاحظ أن خاصية TextState.HorizontalAlignment تعمل فقط في سيناريوهات إنشاء مستندات جديدة. </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | يحصل على التحجيم الأفقي للنص. |
| [getLineSpacing](#getLineSpacing--) | <p> يحصل على تباعد الأسطر للنص. </p> |
| [getRenderingMode](#getRenderingMode--) | يحصل على أو يضبط وضعية العرض للنص. |
| [getStrokingColor](#getStrokingColor--) | يحصل على أو يضبط لون المقدمة للنص. |
| [getTabTag](#getTabTag--) | <p> يمكنك وضع هذا الوسم في النص لتحديد الجدولة. </p> <hr> <p> له تأثير فقط عندما يكون مقترنًا بـ {@code TabStops}. </p> |
| [getTextHeight](#getTextHeight--) | يحصل على ارتفاع النص. |
| [getWordSpacing](#getWordSpacing--) | يحصل على تباعد الكلمات في النص. |
| [isInvisible](#isInvisible--) | يحصل على عدم ظهور النص. هذا يعكس أساسًا حالة {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)})، باستثناء بعض الحالات الخاصة (مثل القص). |
| [isStrikeOut](#isStrikeOut--) | يحصل على الخط المشطوب للنص، الممثل بواسطة كائن {@code TextFragment} |
| [isSubscript](#isSubscript--) | يحصل على أو يضبط النص السفلي. |
| [isSuperscript](#isSuperscript--) | يحصل على النص العلوي. |
| [isUnderline](#isUnderline--) | يحصل على التسطير للنص، الممثل بواسطة كائن {@code TextFragment} |
| [measureHeight](#measureHeight-char-) | يقيس ارتفاع الحرف. |
| [measureString](#measureString-java.lang.String-) | يقيس السلسلة. |
| [measureString](#measureString-java.lang.String-boolean-) | <p> يقيس السلسلة. </p> <hr> <p> insideLine تشير إلى أن السلسلة لم تنتهِ. في حالة قياس جزء من السلسلة الكاملة - يجب أن تكون insideLine true. في حالة قياس السلسلة بأكملها يجب أن تكون insideLine false. بمعنى آخر: عندما تكون insideLine = true يتم أخذ عرض الأحرف فقط في الاعتبار. لا تُؤخذ أي تحولات إضافية في الاعتبار عندما تكون insideLine = false. يتم معالجة نهاية السلسلة بشكل صحيح - تُؤخذ التحولة المائلة في الاعتبار. </p> |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | يضبط لون الخلفية للنص. |
| [setCharacterSpacing](#setCharacterSpacing-float-) | يضبط تباعد الأحرف في النص. |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | يحصل أو يعيّن CoordinateOrigin للنص. إذا كان CoordinateOrigin هو Descender، فإن إحداثي Y للنص يتطابق مع أدنى نقطة للخط. إذا كان CoordinateOrigin هو BaseLine، فإن إحداثي Y للنص يتطابق مع خط الأساس للخط. القيمة الافتراضية هي Descender. إذا كانت قيمة Descent للخط كبيرة جدًا، قد يُظهر النص أعلى من الخطوط الأخرى. في هذه الحالة يمكن اختيار CoordinateOrigin BaseLine للحصول على عرض نص أفضل. |
| [setFont](#setFont-com.aspose.pdf.Font-) | يحصل على خط النص. |
| [setFontSize](#setFontSize-float-) | يضبط حجم الخط للنص. |
| [setFontSizeSuppressedUpdate](#setFontSizeSuppressedUpdate-float-) | يضبط حجم الخط للنص مع تحديث مكبوت. |
| [setFontStyle](#setFontStyle-int-) | يضبط نمط الخط للنص. |
| [setFontSuppressedUpdate](#setFontSuppressedUpdate-com.aspose.pdf.Font-) | يحصل على خط النص مع تحديث مكبوت. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | يضبط لون المقدمة للنص. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> يحدد محاذاة النص أفقياً. </p> <hr> <p> HorizontalAlignment.None يساوي HorizontalAlignment.Left. لاحظ أن خاصية TextState.HorizontalAlignment تعمل فقط في سيناريوهات إنشاء مستندات جديدة. </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | يحدد مقياس النص أفقياً. |
| [setInvisible](#setInvisible-boolean-) | يحدد عدم ظهور النص. هذا يعكس أساساً حالة {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)})، باستثناء بعض الحالات الخاصة (مثل القطع). |
| [setLineSpacing](#setLineSpacing-float-) | <p> يحدد تباعد الأسطر للنص. </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | يحصل على أو يضبط وضعية العرض للنص. |
| [setStrikeOut](#setStrikeOut-boolean-) | يحدد الخط عبر للنص، ممثلاً بواسطة كائن {@code TextFragment} |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | يحصل على أو يضبط لون المقدمة للنص. |
| [setSubscript](#setSubscript-boolean-) | يحصل على أو يضبط النص السفلي. |
| [setSuperscript](#setSuperscript-boolean-) | يحدد النص كحرف مرتفع. |
| [setUnderline](#setUnderline-boolean-) | يحدد التسطير للنص، ممثلاً بواسطة كائن {@code TextFragment} |
| [setWordSpacing](#setWordSpacing-float-) | يحدد تباعد الكلمات في النص. |

### TabstopDefaultValue {#TabstopDefaultValue}
```
public final float TabstopDefaultValue
```

القيمة الافتراضية للجدولة في عرض حرف المسافة للخط الافتراضي.

### TextState {#TextState--}
```
public TextState()
```

ينشئ كائن حالة النص.

### TextState {#TextState-java.awt.Color-}
ينشئ كائن حالة النص.

### TextState {#TextState-java.awt.Color-double-}
ينشئ كائن حالة النص.

### TextState {#TextState-double-}
```
public TextState(double fontSize)
```

ينشئ كائن حالة النص مع تحديد حجم الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontSize |  | حجم الخط. |

### TextState {#TextState-java.lang.String-}
ينشئ كائن حالة النص.

### TextState {#TextState-java.lang.String-boolean-boolean-}
ينشئ كائن حالة النص.

### TextState {#TextState-java.lang.String-double-}
ينشئ كائن حالة النص.

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> يطبّق الإعدادات من textState آخر </p> <hr> <p> سيتم نسخ الخصائص التي تم تغييرها صراحةً فقط. </p>

### calculateFontSize {#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-}
يحسب حجم الخط للمستطيل.

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

<p> يحصل على لون خلفية النص. </p> <hr> <p> لاحظ أن القيمة لا تُحفظ كخاصية نصية داخل المستند. يعمل مُستخرج الخاصية BackgroundColor لكائن في حال تم تعيينه صراحةً مسبقًا باستخدام مُعيّن BackgroundColor لذلك الكائن. تُستخدم الخاصية بواسطة وقت التشغيل في سياق عملية الإنشاء/التعديل الحالية. </p>

**Returns:**
قيمة اللون

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

يحصل على تباعد الأحرف في النص.

**Returns:**
قيمة عائمة

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

يحصل أو يعيّن CoordinateOrigin للنص. إذا كان CoordinateOrigin هو Descender، فإن إحداثي Y للنص يتطابق مع أدنى نقطة للخط. إذا كان CoordinateOrigin هو BaseLine، فإن إحداثي Y للنص يتطابق مع خط الأساس للخط. القيمة الافتراضية هي Descender. إذا كانت قيمة Descent للخط كبيرة جدًا، قد يُظهر النص أعلى من الخطوط الأخرى. في هذه الحالة يمكن اختيار CoordinateOrigin BaseLine للحصول على عرض نص أفضل.

**Returns:**
عنصر CoordinateOrigin

### getFont {#getFont--}
```
public Font getFont()
```

يحصل على خط النص.

**Returns:**
كائن الخط

### getfontSize {#getfontSize--}
```
public float getfontSize()
```

يمثّل طريقة getfontSize

**Returns:**
قيمة عائمة

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

يحصل على حجم الخط للنص.

**Returns:**
قيمة عائمة

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

يضبط نمط الخط للنص.

**Returns:**
عنصر FontStyles @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

يحصل على لون المقدمة للنص.

**Returns:**
قيمة اللون

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> يحصل على المحاذاة الأفقية للنص. </p> <hr> <p> HorizontalAlignment.None يساوي HorizontalAlignment.Left. لاحظ أن خاصية TextState.HorizontalAlignment تعمل فقط في سيناريوهات إنشاء مستندات جديدة. </p>

**Returns:**
قيمة HorizontalAlignment @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

يحصل على التحجيم الأفقي للنص.

**Returns:**
قيمة عائمة

### getLineSpacing {#getLineSpacing--}
```
public float getLineSpacing()
```

<p> يحصل على تباعد الأسطر للنص. </p>

**Returns:**
قيمة عائمة <hr> <p> لاحظ أن القيمة لا تُحفظ كخاصية نص داخل المستند. يعمل getter الخاصية LineSpacing لكائن في حال تم تعيينها صراحةً مسبقاً باستخدام setter الخاص بـ LineSpacing لذلك الكائن. تُستخدم الخاصية من قبل وقت التشغيل في سياق عملية الإنشاء/التعديل الحالية. </p>

### getRenderingMode {#getRenderingMode--}
```
public TextRenderingMode getRenderingMode()
```

يحصل على أو يضبط وضعية العرض للنص.

**Returns:**
عنصر TextRenderingMode @see TextRenderingMode

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

يحصل على أو يضبط لون المقدمة للنص.

**Returns:**
مثيل Color

### getTabTag {#getTabTag--}
```
public final String getTabTag()
```

<p> يمكنك وضع هذا الوسم في النص لتحديد الجدولة. </p> <hr> <p> له تأثير فقط عندما يكون مقترنًا بـ {@code TabStops}. </p>

**Returns:**
قيمة سلسلة "#$TAB"

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

يحصل على ارتفاع النص.

**Returns:**
قيمة عائمة

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

يحصل على تباعد الكلمات في النص.

**Returns:**
قيمة عائمة

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

يحصل على عدم ظهور النص. هذا يعكس أساسًا حالة {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)})، باستثناء بعض الحالات الخاصة (مثل القص).

**Returns:**
قيمة منطقية

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

يحصل على الخط المشطوب للنص، الممثل بواسطة كائن {@code TextFragment}

**Returns:**
قيمة منطقية

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

يحصل على أو يضبط النص السفلي.

**Returns:**
قيمة منطقية

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

يحصل على النص العلوي.

**Returns:**
قيمة منطقية

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

يحصل على التسطير للنص، الممثل بواسطة كائن {@code TextFragment}

**Returns:**
قيمة منطقية

### measureHeight {#measureHeight-char-}
```
public double measureHeight(char character)
```

يقيس ارتفاع الحرف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| حرف |  | الحرف للقياس. |

**Returns:**
ارتفاع الحرف إذا تمكنا من الحصول عليه من الخط؛ وإلا 0.

### measureString {#measureString-java.lang.String-}
يقيس السلسلة.

### measureString {#measureString-java.lang.String-boolean-}
<p> يقيس السلسلة. </p> <hr> <p> insideLine تشير إلى أن السلسلة لم تنتهِ. في حالة قياس جزء من السلسلة الكاملة - يجب أن تكون insideLine true. في حالة قياس السلسلة بأكملها يجب أن تكون insideLine false. بمعنى آخر: عندما تكون insideLine = true يتم أخذ عرض الأحرف فقط في الاعتبار. لا تُؤخذ أي تحولات إضافية في الاعتبار عندما تكون insideLine = false. يتم معالجة نهاية السلسلة بشكل صحيح - تُؤخذ التحولة المائلة في الاعتبار. </p>

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
يضبط لون الخلفية للنص.

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

يضبط تباعد الأحرف في النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
يحصل أو يعيّن CoordinateOrigin للنص. إذا كان CoordinateOrigin هو Descender، فإن إحداثي Y للنص يتطابق مع أدنى نقطة للخط. إذا كان CoordinateOrigin هو BaseLine، فإن إحداثي Y للنص يتطابق مع خط الأساس للخط. القيمة الافتراضية هي Descender. إذا كانت قيمة Descent للخط كبيرة جدًا، قد يُظهر النص أعلى من الخطوط الأخرى. في هذه الحالة يمكن اختيار CoordinateOrigin BaseLine للحصول على عرض نص أفضل.

### setFont {#setFont-com.aspose.pdf.Font-}
يحصل على خط النص.

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

يضبط حجم الخط للنص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setFontSizeSuppressedUpdate {#setFontSizeSuppressedUpdate-float-}
```
public void setFontSizeSuppressedUpdate(float value)
```

يضبط حجم الخط للنص مع تحديث مكبوت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

يضبط نمط الخط للنص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة FontStyles @see FontStyles |

### setFontSuppressedUpdate {#setFontSuppressedUpdate-com.aspose.pdf.Font-}
يحصل على خط النص مع تحديث مكبوت.

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
يضبط لون المقدمة للنص.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> يحدد محاذاة النص أفقياً. </p> <hr> <p> HorizontalAlignment.None يساوي HorizontalAlignment.Left. لاحظ أن خاصية TextState.HorizontalAlignment تعمل فقط في سيناريوهات إنشاء مستندات جديدة. </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

يحدد مقياس النص أفقياً.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

يحدد عدم ظهور النص. هذا يعكس أساساً حالة {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)})، باستثناء بعض الحالات الخاصة (مثل القطع).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setLineSpacing {#setLineSpacing-float-}
```
public void setLineSpacing(float value)
```

<p> يحدد تباعد الأسطر للنص. </p>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة <hr> <p> لاحظ أن القيمة لا تُحفظ كخاصية نص داخل المستند. يعمل getter الخاصية LineSpacing لكائن في حال تم تعيينها صراحةً مسبقاً باستخدام setter الخاص بـ LineSpacing لذلك الكائن. تُستخدم الخاصية من قبل وقت التشغيل في سياق عملية الإنشاء/التعديل الحالية. </p> |

### setRenderingMode {#setRenderingMode-com.aspose.pdf.TextRenderingMode-}
يحصل على أو يضبط وضعية العرض للنص.

### setStrikeOut {#setStrikeOut-boolean-}
```
public void setStrikeOut(boolean value)
```

يحدد الخط عبر للنص، ممثلاً بواسطة كائن {@code TextFragment}

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setStrokingColor {#setStrokingColor-com.aspose.pdf.Color-}
يحصل على أو يضبط لون المقدمة للنص.

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

يحصل على أو يضبط النص السفلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

يحدد النص كحرف مرتفع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setUnderline {#setUnderline-boolean-}
```
public void setUnderline(boolean value)
```

يحدد التسطير للنص، ممثلاً بواسطة كائن {@code TextFragment}

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setWordSpacing {#setWordSpacing-float-}
```
public void setWordSpacing(float value)
```

يحدد تباعد الكلمات في النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |
