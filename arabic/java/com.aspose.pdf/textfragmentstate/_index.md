---
title: "TextFragmentState"
linktitle: "TextFragmentState"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "<p> يمثل حالة نصية لمجزوء النص. </p> <hr> <pre> يوضح المثال كيفية تغيير لون النص وحجم الخط للنص باستخدام كائن {@code TextState}. // Open.</pre>"
type: docs
weight: 5150
url: /ar/java/com.aspose.pdf/textfragmentstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState com.aspose.pdf.TextFragmentState, com.aspose.pdf.TextState, com.aspose.pdf.TextFragmentState

```
public final class TextFragmentState extends TextState
```

<p> يمثل حالة نصية لمجزوء النص. </p> <hr> <pre> يوضح المثال كيفية تغيير لون النص وحجم الخط للنص باستخدام كائن {@code TextState}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> يوفر طريقة لتغيير الخصائص التالية للنص: الخط ({@code TextFragmentState.Font} property) حجم الخط ({@code TextFragmentState.FontSize} property) نمط الخط ({@code TextFragmentState.FontStyle} property) لون المقدمة ({@code TextFragmentState.ForegroundColor} property) لون الخلفية ({@code TextFragmentState.BackgroundColor} property) </p> <p> لاحظ أن تغيير خصائص {@code TextFragmentState} قد يغير مجموعة {@code TextFragment.Segments} الداخلية لأن TextFragment هو كائن تجميعي وقد يعيد ترتيب المقاطع الداخلية أو يدمجها في مقطع واحد. إذا كان متطلباتك هي ترك مجموعة {@code TextFragment.Segments} دون تغيير، يرجى تغيير المقاطع الداخلية بشكل فردي. </p> @see TextFragmentAbsorber @see IDocument

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextFragmentState](#TextFragmentState-com.aspose.pdf.TextFragment-) | يُنشئ نسخة جديدة من كائن {@code TextFragmentState} باستخدام كائن {@code TextFragment} المحدد. لا يُدعم تهيئة {@code TextFragmentState}. يتوفر TextFragmentState فقط مع خاصية {@code TextFragment.TextState}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> يطبق الإعدادات من textState آخر </p> |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-boolean-) | يطبق الإعدادات من textState آخر |
| [getBackgroundColor](#getBackgroundColor--) | يضبط لون خلفية النص، الممثل بكائن {@code TextFragment} |
| [getCharacterSpacing](#getCharacterSpacing--) | يحصل على تباعد الأحرف للنص، الممثلة بواسطة كائن {@code TextFragment} object. |
| [getCoordinateOrigin](#getCoordinateOrigin--) | يحصل أو يعيّن CoordinateOrigin للنص. إذا كان CoordinateOrigin هو Descender، فإن إحداثي Y للنص يتطابق مع أدنى نقطة للخط. إذا كان CoordinateOrigin هو BaseLine، فإن إحداثي Y للنص يتطابق مع خط الأساس للخط. القيمة الافتراضية هي Descender. إذا كانت قيمة Descent للخط كبيرة جدًا، قد يُظهر النص أعلى من الخطوط الأخرى. في هذه الحالة يمكن اختيار CoordinateOrigin BaseLine للحصول على عرض نص أفضل. |
| [getDrawTextRectangleBorder](#getDrawTextRectangleBorder--) | يحصل على ما إذا كان علم رسم حدود مستطيل النص مفعلاً. |
| [getFont](#getFont--) | يحصل على خط النص، الممثلة بواسطة كائن {@code TextFragment} object |
| [getFontSize](#getFontSize--) | يحصل على حجم خط النص، الممثلة بواسطة كائن {@code TextFragment} object |
| [getFontStyle](#getFontStyle--) | يضبط نمط خط النص، الممثلة بواسطة كائن {@code TextFragment} object |
| [getForegroundColor](#getForegroundColor--) | يحصل على لون المقدمة للنص، الممثلة بواسطة كائن {@code TextFragment} object |
| [getFormattingOptions](#getFormattingOptions--) | يحصل أو يضبط خيارات التنسيق. سيكون ضبط الخيارات فعالاً فقط في سيناريوهات المولد. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> يحصل على محاذاة أفقية للنص. </p> <hr> <p> HorizontalAlignment.None يساوي HorizontalAlignment.Left. لاحظ أن خاصية TextFragmentState.VerticalAlignment تعمل فقط في سيناريوهات إنشاء مستندات جديدة. </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | يحصل على مقياس أفقي للنص، الممثلة بواسطة كائن {@code TextFragment} object. |
| [getLineSpacing](#getLineSpacing--) | <p> يحصل على تباعد الأسطر للنص. </p> |
| [getRenderingMode](#getRenderingMode--) | يحصل أو يضبط وضعية العرض للنص. |
| [getRotation](#getRotation--) | يحصل أو يضبط زاوية الدوران بالدرجات. |
| [getStrokingColor](#getStrokingColor--) | يحصل أو يضبط عمليات تلوين الخط في عرض {@code TextFragment} (تحديد النص، حدود المستطيل) |
| [getTabStops](#getTabStops--) | <p> يحصل على نقاط التبويب للنص. </p> <hr> <p> لاحظ أن خاصية Tabstops تعمل فقط في سيناريوهات إنشاء مستندات جديدة. يمكن إضافة نقاط التبويب أثناء تهيئة {@code TextFragment}. يجب إنشاء نقاط التبويب قبل النص. </p> |
| [getTextHeight](#getTextHeight--) | يحصل على ارتفاع النص، الممثلة بواسطة كائن {@code TextFragment} object |
| [getWordSpacing](#getWordSpacing--) | يحصل على تباعد الكلمات في النص. |
| [isFitRectangle](#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-) | يتحقق مما إذا كان يمكن وضع السلسلة المدخلة داخل المستطيل المحدد. |
| [isInvisible](#isInvisible--) | يحصل على عدم وضوح النص. |
| [isStrikeOut](#isStrikeOut--) | يحصل أو يضبط شطب النص، الممثلة بواسطة كائن {@link TextFragment} object |
| [isSubscript](#isSubscript--) | يحصل أو يضبط النص كمنخفض، الممثلة بواسطة كائن {@code TextFragment} object. |
| [isSuperscript](#isSuperscript--) | يحصل أو يضبط النص كمرتفع، الممثلة بواسطة كائن {@code TextFragment} object. |
| [isUnderline](#isUnderline--) | يحصل أو يضبط تسطير النص، الممثلة بواسطة كائن {@link TextFragment} object |
| [measureHeight](#measureHeight-char-) | يقيس ارتفاع الحرف. |
| [measureString](#measureString-java.lang.String-) | يقيس السلسلة. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | يضبط لون الخلفية للنص، الممثلة بواسطة كائن TextFragment object |
| [setCharacterSpacing](#setCharacterSpacing-float-) | يضبط تباعد الأحرف للنص، الممثلة بواسطة كائن {@code TextFragment} object. |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | يحصل أو يعيّن CoordinateOrigin للنص. إذا كان CoordinateOrigin هو Descender، فإن إحداثي Y للنص يتطابق مع أدنى نقطة للخط. إذا كان CoordinateOrigin هو BaseLine، فإن إحداثي Y للنص يتطابق مع خط الأساس للخط. القيمة الافتراضية هي Descender. إذا كانت قيمة Descent للخط كبيرة جدًا، قد يُظهر النص أعلى من الخطوط الأخرى. في هذه الحالة يمكن اختيار CoordinateOrigin BaseLine للحصول على عرض نص أفضل. |
| [setDrawTextRectangleBorder](#setDrawTextRectangleBorder-boolean-) | يضبط ما إذا كان علم رسم حدود مستطيل النص مفعلاً. |
| [setFont](#setFont-com.aspose.pdf.Font-) | يضبط خط النص، الممثلة بواسطة كائن {@code TextFragment} object |
| [setFontSize](#setFontSize-float-) | يضبط حجم خط النص، الممثلة بواسطة كائن {@code TextFragment} object |
| [setFontStyle](#setFontStyle-int-) | يضبط نمط خط النص، الممثلة بواسطة كائن {@link TextFragment} object |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | يضبط لون المقدمة للنص، الممثل بواسطة كائن {@code TextFragment} object |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | يحصل أو يضبط خيارات التنسيق. سيكون ضبط الخيارات فعالاً فقط في سيناريوهات المولد. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> يضبط محاذاة أفقية للنص. </p> <hr> <p> HorizontalAlignment.None يساوي HorizontalAlignment.Left. لاحظ أن خاصية TextFragmentState.VerticalAlignment تعمل فقط في سيناريوهات إنشاء المستندات الجديدة. </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | يضبط التحجيم الأفقي للنص، الممثل بواسطة كائن {@code TextFragment} object. |
| [setInvisible](#setInvisible-boolean-) | يضبط إخفاء النص. |
| [setLineSpacing](#setLineSpacing-float-) | <p> يحدد تباعد الأسطر للنص. </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | يحصل أو يضبط وضعية العرض للنص. |
| [setRotation](#setRotation-double-) | يحصل أو يضبط زاوية الدوران بالدرجات. |
| [setStrikeOut](#setStrikeOut-boolean-) | يحدد الخط عبر للنص، ممثلاً بواسطة كائن {@code TextFragment} |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | يحصل أو يضبط عمليات تلوين الخط في عرض {@code TextFragment} (تحديد النص، حدود المستطيل) |
| [setSubscript](#setSubscript-boolean-) | يحصل أو يضبط النص كمنخفض، الممثلة بواسطة كائن {@code TextFragment} object. |
| [setSuperscript](#setSuperscript-boolean-) | يحصل أو يضبط النص كمرتفع، الممثلة بواسطة كائن {@code TextFragment} object. |
| [setUnderline](#setUnderline-boolean-) | يحدد التسطير للنص، ممثلاً بواسطة كائن {@code TextFragment} |
| [setWordSpacing](#setWordSpacing-float-) | يحدد تباعد الكلمات في النص. |

### TextFragmentState {#TextFragmentState-com.aspose.pdf.TextFragment-}
يُنشئ نسخة جديدة من كائن {@code TextFragmentState} باستخدام كائن {@code TextFragment} المحدد. لا يُدعم تهيئة {@code TextFragmentState}. يتوفر TextFragmentState فقط مع خاصية {@code TextFragment.TextState}.

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> يطبق الإعدادات من textState آخر </p>

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-boolean-}
يطبق الإعدادات من textState آخر

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

يضبط لون خلفية النص، الممثل بكائن {@code TextFragment}

**Returns:**
قيمة كائن Color

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

يحصل على تباعد الأحرف للنص، الممثلة بواسطة كائن {@code TextFragment} object.

**Returns:**
قيمة عائمة

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

يحصل أو يعيّن CoordinateOrigin للنص. إذا كان CoordinateOrigin هو Descender، فإن إحداثي Y للنص يتطابق مع أدنى نقطة للخط. إذا كان CoordinateOrigin هو BaseLine، فإن إحداثي Y للنص يتطابق مع خط الأساس للخط. القيمة الافتراضية هي Descender. إذا كانت قيمة Descent للخط كبيرة جدًا، قد يُظهر النص أعلى من الخطوط الأخرى. في هذه الحالة يمكن اختيار CoordinateOrigin BaseLine للحصول على عرض نص أفضل.

**Returns:**
عنصر CoordinateOrigin

### getDrawTextRectangleBorder {#getDrawTextRectangleBorder--}
```
public boolean getDrawTextRectangleBorder()
```

يحصل على ما إذا كان علم رسم حدود مستطيل النص مفعلاً.

**Returns:**
قيمة منطقية

### getFont {#getFont--}
```
public Font getFont()
```

يحصل على خط النص، الممثلة بواسطة كائن {@code TextFragment} object

**Returns:**
قيمة الخط

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

يحصل على حجم خط النص، الممثلة بواسطة كائن {@code TextFragment} object

**Returns:**
قيمة عائمة

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

يضبط نمط خط النص، الممثلة بواسطة كائن {@code TextFragment} object

**Returns:**
عنصر FontStyles @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

يحصل على لون المقدمة للنص، الممثلة بواسطة كائن {@code TextFragment} object

**Returns:**
كائن Color

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

يحصل أو يضبط خيارات التنسيق. سيكون ضبط الخيارات فعالاً فقط في سيناريوهات المولد.

**Returns:**
مثيل TextFormattingOptions

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> يحصل على محاذاة أفقية للنص. </p> <hr> <p> HorizontalAlignment.None يساوي HorizontalAlignment.Left. لاحظ أن خاصية TextFragmentState.VerticalAlignment تعمل فقط في سيناريوهات إنشاء مستندات جديدة. </p>

**Returns:**
قيمة HorizontalAlignment @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

يحصل على مقياس أفقي للنص، الممثلة بواسطة كائن {@code TextFragment} object.

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

يحصل أو يضبط وضعية العرض للنص.

**Returns:**
عنصر TextRenderingMode

### getRotation {#getRotation--}
```
public double getRotation()
```

يحصل أو يضبط زاوية الدوران بالدرجات.

**Returns:**
قيمة double

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

يحصل أو يضبط عمليات تلوين الخط في عرض {@code TextFragment} (تحديد النص، حدود المستطيل)

**Returns:**
مثيل Color

### getTabStops {#getTabStops--}
```
public TabStops getTabStops()
```

<p> يحصل على نقاط التبويب للنص. </p> <hr> <p> لاحظ أن خاصية Tabstops تعمل فقط في سيناريوهات إنشاء مستندات جديدة. يمكن إضافة نقاط التبويب أثناء تهيئة {@code TextFragment}. يجب إنشاء نقاط التبويب قبل النص. </p>

**Returns:**
كائن TabStops

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

يحصل على ارتفاع النص، الممثلة بواسطة كائن {@code TextFragment} object

**Returns:**
قيمة عائمة

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

يحصل على تباعد الكلمات في النص.

**Returns:**
قيمة عائمة

### isFitRectangle {#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-}
يتحقق مما إذا كان يمكن وضع السلسلة المدخلة داخل المستطيل المحدد.

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

يحصل على عدم وضوح النص.

**Returns:**
قيمة منطقية

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

يحصل أو يضبط شطب النص، الممثلة بواسطة كائن {@link TextFragment} object

**Returns:**
قيمة منطقية

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

يحصل أو يضبط النص كمنخفض، الممثلة بواسطة كائن {@code TextFragment} object.

**Returns:**
قيمة منطقية

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

يحصل أو يضبط النص كمرتفع، الممثلة بواسطة كائن {@code TextFragment} object.

**Returns:**
قيمة منطقية

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

يحصل أو يضبط تسطير النص، الممثلة بواسطة كائن {@link TextFragment} object

**Returns:**
قيمة منطقية

### measureHeight {#measureHeight-char-}
```
public final double measureHeight(char character)
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

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
يضبط لون الخلفية للنص، الممثلة بواسطة كائن TextFragment object

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

يضبط تباعد الأحرف للنص، الممثلة بواسطة كائن {@code TextFragment} object.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
يحصل أو يعيّن CoordinateOrigin للنص. إذا كان CoordinateOrigin هو Descender، فإن إحداثي Y للنص يتطابق مع أدنى نقطة للخط. إذا كان CoordinateOrigin هو BaseLine، فإن إحداثي Y للنص يتطابق مع خط الأساس للخط. القيمة الافتراضية هي Descender. إذا كانت قيمة Descent للخط كبيرة جدًا، قد يُظهر النص أعلى من الخطوط الأخرى. في هذه الحالة يمكن اختيار CoordinateOrigin BaseLine للحصول على عرض نص أفضل.

### setDrawTextRectangleBorder {#setDrawTextRectangleBorder-boolean-}
```
public void setDrawTextRectangleBorder(boolean value)
```

يضبط ما إذا كان علم رسم حدود مستطيل النص مفعلاً.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setFont {#setFont-com.aspose.pdf.Font-}
يضبط خط النص، الممثلة بواسطة كائن {@code TextFragment} object

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

يضبط حجم خط النص، الممثلة بواسطة كائن {@code TextFragment} object

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

يضبط نمط خط النص، الممثلة بواسطة كائن {@link TextFragment} object

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int @see FontStyles |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
يضبط لون المقدمة للنص، الممثل بواسطة كائن {@code TextFragment} object

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
يحصل أو يضبط خيارات التنسيق. سيكون ضبط الخيارات فعالاً فقط في سيناريوهات المولد.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> يضبط محاذاة أفقية للنص. </p> <hr> <p> HorizontalAlignment.None يساوي HorizontalAlignment.Left. لاحظ أن خاصية TextFragmentState.VerticalAlignment تعمل فقط في سيناريوهات إنشاء المستندات الجديدة. </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

يضبط التحجيم الأفقي للنص، الممثل بواسطة كائن {@code TextFragment} object.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

يضبط إخفاء النص.

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
يحصل أو يضبط وضعية العرض للنص.

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

يحصل أو يضبط زاوية الدوران بالدرجات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

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
يحصل أو يضبط عمليات تلوين الخط في عرض {@code TextFragment} (تحديد النص، حدود المستطيل)

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

يحصل أو يضبط النص كمنخفض، الممثلة بواسطة كائن {@code TextFragment} object.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

يحصل أو يضبط النص كمرتفع، الممثلة بواسطة كائن {@code TextFragment} object.

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
