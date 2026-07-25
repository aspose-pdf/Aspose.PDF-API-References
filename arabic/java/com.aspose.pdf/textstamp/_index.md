---
title: "TextStamp"
linktitle: "TextStamp"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل ختمًا نصيًا."
type: docs
weight: 5320
url: /ar/java/com.aspose.pdf/textstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp

```
public class TextStamp extends Stamp
```

يمثل ختمًا نصيًا.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-) | يُنشئ مثيلًا جديدًا للفئة {@code TextStamp} مع كائن formattedText |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-) | يُنشئ مثيلًا جديدًا للفئة {@code TextStamp} مع كائن formattedText |
| [TextStamp](#TextStamp-java.lang.String-) | يُنشئ مثيلًا جديدًا للفئة {@code TextStamp}. |
| [TextStamp](#TextStamp-java.lang.String-com.aspose.pdf.TextState-) | يُنشئ مثيلًا جديدًا للفئة TextStamp. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAutoAdjustFontSizePrecision](#getAutoAdjustFontSizePrecision--) | ضبط دقة حجم الخط تلقائيًا. القيمة الافتراضية: 0.1؛ |
| [getAutoAdjustFontSizeToFitStampRectangle](#getAutoAdjustFontSizeToFitStampRectangle--) | إذا تم التفعيل، سيتم ضبط حجم الخط تلقائيًا ليتناسب مع مستطيل الختم بالحجم: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) و {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). العرض والارتفاع الافتراضيان مستمدان من مستطيل الصفحة. |
| [getDefaultFont](#getDefaultFont--) | يعيد الخط الافتراضي |
| [getDefaultFontSize](#getDefaultFontSize--) | حجم الخط الافتراضي |
| [getDraw](#getDraw--) | تحدد هذه الخاصية طريقة رسم الختم على الصفحة. إذا كان Draw = true يتم رسم الختم كعامل رسومي وإذا كان draw = false يتم رسم الختم كنص. |
| [getFontSize](#getFontSize--) | حجم الخط الفعلي بعد وضع الختم. (قد يختلف عن حجم الخط الأولي المقدم عبر المُنشئ إذا تم تمكين خيار 'AutoAdjustFontSizeToFitStampRectangle'.) |
| [getHeight](#getHeight--) | الارتفاع المطلوب للختم على الصفحة. |
| [getMaxRowWidth](#getMaxRowWidth--) | الحد الأقصى لارتفاع الصف لخيار WordWrap. |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | يحصل أو يعيّن الوضع الذي يحدد السلوك في حالة عدم احتواء الخطوط على الأحرف المطلوبة. |
| [getReplacementFont](#getReplacementFont--) | يحصل أو يعيّن الخط المستخدم للاستبدال إذا لم يحتوي خط المستخدم على الحرف المطلوب. |
| [getTextAlignment](#getTextAlignment--) | محاذاة النص داخل الختم. |
| [getTextState](#getTextState--) | يحصل على خصائص النص للختم. راجع {@code TextState} للحصول على التفاصيل. |
| [getTreatYIndentAsBaseLine](#getTreatYIndentAsBaseLine--) | يحدد أصل الإحداثيات لوضع النص. إذا كان TreatYIndentAsBaseLine = true (القيمة الافتراضية عندما Draw = true) سيتم اعتبار قيمة YIndent كخط أساس للنص. إذا كان TreatYIndentAsBaseLine = false (القيمة الافتراضية عندما Draw = false) سيتم اعتبار قيمة YIndent كقاع (خط النزول) للنص. |
| [getValue](#getValue--) | يحصل على قيمة السلسلة المستخدمة كختم على الصفحة. |
| [getWidth](#getWidth--) | العرض المطلوب للختم على الصفحة. |
| [getWordWrapMode](#getWordWrapMode--) | يحصل أو يعيّن وضع التفاف الكلمات لتصيير النص. |
| [isJustify](#isJustify--) | يحدد محاذاة النص. إذا تم تعيين هذه الخاصية إلى true، يتم محاذاة الحافتين اليسرى واليمنى للنص. القيمة الافتراضية: false. |
| [isScale](#isScale--) | يحدد تحجيم النص. إذا تم تعيين هذه الخاصية إلى true وتم تحديد قيمة Width، سيتم تحجيم النص ليتناسب مع العرض المحدد. |
| [isWordWrap](#isWordWrap--) | يحدد التفاف الكلمات. إذا تم تعيين هذه الخاصية إلى true وتم تحديد قيمة Width، سيتم تقسيم النص إلى عدة أسطر ليتناسب مع العرض المحدد. القيمة الافتراضية: false. |
| [put](#put-com.aspose.pdf.Page-) | يضيف ختمًا نصيًا على الصفحة. |
| [setAutoAdjustFontSizePrecision](#setAutoAdjustFontSizePrecision-float-) | ضبط دقة حجم الخط تلقائيًا. القيمة الافتراضية: 0.1؛ |
| [setAutoAdjustFontSizeToFitStampRectangle](#setAutoAdjustFontSizeToFitStampRectangle-boolean-) | إذا تم التفعيل، سيتم ضبط حجم الخط تلقائيًا ليتناسب مع مستطيل الختم بالحجم: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) و {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). العرض والارتفاع الافتراضيان مستمدان من مستطيل الصفحة. |
| [setDraw](#setDraw-boolean-) | تحدد هذه الخاصية طريقة رسم الختم على الصفحة. إذا كان Draw = true يتم رسم الختم كعامل رسومي وإذا كان draw = false يتم رسم الختم كنص. |
| [setHeight](#setHeight-double-) | الارتفاع المطلوب للختم على الصفحة. |
| [setJustify](#setJustify-boolean-) | يحدد محاذاة النص. إذا تم تعيين هذه الخاصية إلى true، يتم محاذاة الحافتين اليسرى واليمنى للنص. القيمة الافتراضية: false. |
| [setMaxRowWidth](#setMaxRowWidth-double-) | الحد الأقصى لارتفاع الصف لخيار WordWrap. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-int-) | يحصل أو يعيّن الوضع الذي يحدد السلوك في حالة عدم احتواء الخطوط على الأحرف المطلوبة. |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | يحصل أو يعيّن الخط المستخدم للاستبدال إذا لم يحتوي خط المستخدم على الحرف المطلوب. |
| [setScale](#setScale-boolean-) | يحدد تحجيم النص. إذا تم تعيين هذه الخاصية إلى true وتم تحديد قيمة Width، سيتم تحجيم النص ليتناسب مع العرض المحدد. |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | محاذاة النص داخل الختم. |
| [setTreatYIndentAsBaseLine](#setTreatYIndentAsBaseLine-boolean-) | يحدد أصل الإحداثيات لوضع النص. إذا كان TreatYIndentAsBaseLine = true (القيمة الافتراضية عندما Draw = true) سيتم اعتبار قيمة YIndent كخط أساس للنص. إذا كان TreatYIndentAsBaseLine = false (القيمة الافتراضية عندما Draw = false) سيتم اعتبار قيمة YIndent كقاع (خط النزول) للنص. |
| [setValue](#setValue-java.lang.String-) | يعيّن قيمة السلسلة المستخدمة كختم على الصفحة. |
| [setWidth](#setWidth-double-) | العرض المطلوب للختم على الصفحة. |
| [setWordWrap](#setWordWrap-boolean-) | يحدد التفاف الكلمات. إذا تم تعيين هذه الخاصية إلى true وتم تحديد قيمة Width، سيتم تقسيم النص إلى عدة أسطر ليتناسب مع العرض المحدد. القيمة الافتراضية: false. |
| [setWordWrapMode](#setWordWrapMode-int-) | يحصل أو يعيّن وضع التفاف الكلمات لتصيير النص. |

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-}
يُنشئ مثيلًا جديدًا للفئة {@code TextStamp} مع كائن formattedText

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-}
يُنشئ مثيلًا جديدًا للفئة {@code TextStamp} مع كائن formattedText

### TextStamp {#TextStamp-java.lang.String-}
يُنشئ مثيلًا جديدًا للفئة {@code TextStamp}.

### TextStamp {#TextStamp-java.lang.String-com.aspose.pdf.TextState-}
يُنشئ مثيلًا جديدًا للفئة TextStamp.

### getAutoAdjustFontSizePrecision {#getAutoAdjustFontSizePrecision--}
```
public final float getAutoAdjustFontSizePrecision()
```

ضبط دقة حجم الخط تلقائيًا. القيمة الافتراضية: 0.1؛

**Returns:**
قيمة عائمة

### getAutoAdjustFontSizeToFitStampRectangle {#getAutoAdjustFontSizeToFitStampRectangle--}
```
public final boolean getAutoAdjustFontSizeToFitStampRectangle()
```

إذا تم التفعيل، سيتم ضبط حجم الخط تلقائيًا ليتناسب مع مستطيل الختم بالحجم: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) و {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). العرض والارتفاع الافتراضيان مستمدان من مستطيل الصفحة.

**Returns:**
قيمة منطقية

### getDefaultFont {#getDefaultFont--}
```
public static Font getDefaultFont()
```

يعيد الخط الافتراضي

**Returns:**
كائن com.aspose.pdf.Font

### getDefaultFontSize {#getDefaultFontSize--}
```
public static float getDefaultFontSize()
```

حجم الخط الافتراضي

**Returns:**
قيمة عائمة

### getDraw {#getDraw--}
```
public boolean getDraw()
```

تحدد هذه الخاصية طريقة رسم الختم على الصفحة. إذا كان Draw = true يتم رسم الختم كعامل رسومي وإذا كان draw = false يتم رسم الختم كنص.

**Returns:**
قيمة منطقية

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

حجم الخط الفعلي بعد وضع الختم. (قد يختلف عن حجم الخط الأولي المقدم عبر المُنشئ إذا تم تمكين خيار 'AutoAdjustFontSizeToFitStampRectangle'.)

**Returns:**
قيمة عائمة

### getHeight {#getHeight--}
```
public double getHeight()
```

الارتفاع المطلوب للختم على الصفحة.

**Returns:**
قيمة double

### getMaxRowWidth {#getMaxRowWidth--}
```
public double getMaxRowWidth()
```

الحد الأقصى لارتفاع الصف لخيار WordWrap.

**Returns:**
قيمة double

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public final int getNoCharacterBehavior()
```

يحصل أو يعيّن الوضع الذي يحدد السلوك في حالة عدم احتواء الخطوط على الأحرف المطلوبة.

**Returns:**
عنصر NoCharacterAction

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

يحصل أو يعيّن الخط المستخدم للاستبدال إذا لم يحتوي خط المستخدم على الحرف المطلوب.

**Returns:**
كائن Font

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

محاذاة النص داخل الختم.

**Returns:**
قيمة HorizontalAlignment @see HorizontalAlignment

### getTextState {#getTextState--}
```
public TextState getTextState()
```

يحصل على خصائص النص للختم. راجع {@code TextState} للحصول على التفاصيل.

**Returns:**
عنصر TextState

### getTreatYIndentAsBaseLine {#getTreatYIndentAsBaseLine--}
```
public boolean getTreatYIndentAsBaseLine()
```

يحدد أصل الإحداثيات لوضع النص. إذا كان TreatYIndentAsBaseLine = true (القيمة الافتراضية عندما Draw = true) سيتم اعتبار قيمة YIndent كخط أساس للنص. إذا كان TreatYIndentAsBaseLine = false (القيمة الافتراضية عندما Draw = false) سيتم اعتبار قيمة YIndent كقاع (خط النزول) للنص.

**Returns:**
قيمة منطقية

### getValue {#getValue--}
```
public String getValue()
```

يحصل على قيمة السلسلة المستخدمة كختم على الصفحة.

**Returns:**
قيمة سلسلة

### getWidth {#getWidth--}
```
public double getWidth()
```

العرض المطلوب للختم على الصفحة.

**Returns:**
قيمة double

### getWordWrapMode {#getWordWrapMode--}
```
public final int getWordWrapMode()
```

يحصل أو يعيّن وضع التفاف الكلمات لتصيير النص.

**Returns:**
عنصر WordWrapMode

### isJustify {#isJustify--}
```
public boolean isJustify()
```

يحدد محاذاة النص. إذا تم تعيين هذه الخاصية إلى true، يتم محاذاة الحافتين اليسرى واليمنى للنص. القيمة الافتراضية: false.

**Returns:**
قيمة منطقية

### isScale {#isScale--}
```
public boolean isScale()
```

يحدد تحجيم النص. إذا تم تعيين هذه الخاصية إلى true وتم تحديد قيمة Width، سيتم تحجيم النص ليتناسب مع العرض المحدد.

**Returns:**
قيمة منطقية

### isWordWrap {#isWordWrap--}
```
@Deprecated public boolean isWordWrap()
```

يحدد التفاف الكلمات. إذا تم تعيين هذه الخاصية إلى true وتم تحديد قيمة Width، سيتم تقسيم النص إلى عدة أسطر ليتناسب مع العرض المحدد. القيمة الافتراضية: false.

**Returns:**
قيمة منطقية @deprecated "استخدم WordWrapMode بدلاً من ذلك."

### put {#put-com.aspose.pdf.Page-}
يضيف ختمًا نصيًا على الصفحة.

### setAutoAdjustFontSizePrecision {#setAutoAdjustFontSizePrecision-float-}
```
public final void setAutoAdjustFontSizePrecision(float value)
```

ضبط دقة حجم الخط تلقائيًا. القيمة الافتراضية: 0.1؛

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setAutoAdjustFontSizeToFitStampRectangle {#setAutoAdjustFontSizeToFitStampRectangle-boolean-}
```
public final void setAutoAdjustFontSizeToFitStampRectangle(boolean value)
```

إذا تم التفعيل، سيتم ضبط حجم الخط تلقائيًا ليتناسب مع مستطيل الختم بالحجم: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) و {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). العرض والارتفاع الافتراضيان مستمدان من مستطيل الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setDraw {#setDraw-boolean-}
```
public void setDraw(boolean value)
```

تحدد هذه الخاصية طريقة رسم الختم على الصفحة. إذا كان Draw = true يتم رسم الختم كعامل رسومي وإذا كان draw = false يتم رسم الختم كنص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

الارتفاع المطلوب للختم على الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

يحدد محاذاة النص. إذا تم تعيين هذه الخاصية إلى true، يتم محاذاة الحافتين اليسرى واليمنى للنص. القيمة الافتراضية: false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setMaxRowWidth {#setMaxRowWidth-double-}
```
public void setMaxRowWidth(double value)
```

الحد الأقصى لارتفاع الصف لخيار WordWrap.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setNoCharacterBehavior {#setNoCharacterBehavior-int-}
```
public final void setNoCharacterBehavior(int value)
```

يحصل أو يعيّن الوضع الذي يحدد السلوك في حالة عدم احتواء الخطوط على الأحرف المطلوبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر NoCharacterAction |

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
يحصل أو يعيّن الخط المستخدم للاستبدال إذا لم يحتوي خط المستخدم على الحرف المطلوب.

### setScale {#setScale-boolean-}
```
public void setScale(boolean value)
```

يحدد تحجيم النص. إذا تم تعيين هذه الخاصية إلى true وتم تحديد قيمة Width، سيتم تحجيم النص ليتناسب مع العرض المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
محاذاة النص داخل الختم.

### setTreatYIndentAsBaseLine {#setTreatYIndentAsBaseLine-boolean-}
```
public void setTreatYIndentAsBaseLine(boolean value)
```

يحدد أصل الإحداثيات لوضع النص. إذا كان TreatYIndentAsBaseLine = true (القيمة الافتراضية عندما Draw = true) سيتم اعتبار قيمة YIndent كخط أساس للنص. إذا كان TreatYIndentAsBaseLine = false (القيمة الافتراضية عندما Draw = false) سيتم اعتبار قيمة YIndent كقاع (خط النزول) للنص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setValue {#setValue-java.lang.String-}
يعيّن قيمة السلسلة المستخدمة كختم على الصفحة.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

العرض المطلوب للختم على الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setWordWrap {#setWordWrap-boolean-}
```
@Deprecated public void setWordWrap(boolean value)
```

يحدد التفاف الكلمات. إذا تم تعيين هذه الخاصية إلى true وتم تحديد قيمة Width، سيتم تقسيم النص إلى عدة أسطر ليتناسب مع العرض المحدد. القيمة الافتراضية: false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية @deprecated "استخدم WordWrapMode بدلاً من ذلك." |

### setWordWrapMode {#setWordWrapMode-int-}
```
public final void setWordWrapMode(int value)
```

يحصل أو يعيّن وضع التفاف الكلمات لتصيير النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر WordWrapMode @see WordWrapMode |
