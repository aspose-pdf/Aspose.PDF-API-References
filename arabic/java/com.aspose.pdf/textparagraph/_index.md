---
title: "TextParagraph"
linktitle: "TextParagraph"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "<p> يمثل فقرات النص ككائن نص متعدد الأسطر. </p> <hr> <pre> يوضح المثال كيفية إنشاء كائن فقرة نصية وإلحاقه بصفحة Pdf. Document doc."
type: docs
weight: 5200
url: /ar/java/com.aspose.pdf/textparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextParagraph

```
public final class TextParagraph extends Object
```

<p> يمثل فقرات النص ككائن نص متعدد الأسطر. </p> <hr> <pre> يوضح المثال كيفية إنشاء كائن فقرة نصية وإلحاقه بصفحة PDF. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // إنشاء فقرة نصية TextParagraph paragraph = new TextParagraph(); // تعيين مستطيل الفقرة paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // تعيين خيارات التفاف الكلمات paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // إلحاق سطر النص paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // إلحاق الفقرة بصفحة PDF باستخدام TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // حفظ مستند PDF doc.save(outFile); </pre>

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextParagraph](#TextParagraph--) | ينشئ كائن {@code TextParagraph}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [appendLine](#appendLine-java.lang.String-) | يلحق سطر نص |
| [appendLine](#appendLine-java.lang.String-float-) | يلحق سطر نص. |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-) | يلحق سطر نص مع معلمات حالة النص. |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-float-) | يلحق سطر نص مع معلمات حالة النص. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-) | يلحق سطر نص مع معلمات حالة النص. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-) | يلحق سطر نص مع معلمات حالة النص. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-) | يلحق سطر نص مع معلمات حالة النص. |
| [beginEdit](#beginEdit--) | يبدأ تحرير TextParagraph. <p> يحسن أداء تعبئة TextParagraph. يتم تعليق أي حساب تخطيط حتى يتم استدعاء طريقة EndEdit. <p> لاحظ أن استدعاء الطريقة لا يمكن أن يكون متداخلًا. </p> |
| [endEdit](#endEdit--) | ينهي تحرير TextParagraph. <p> يحسن أداء تعبئة TextParagraph. يتم تعليق أي حساب تخطيط حتى يتم استدعاء طريقة EndEdit. <p> لاحظ أن استدعاء الطريقة لا يمكن أن يكون متداخلًا. </p> |
| [getFirstLineIndent](#getFirstLineIndent--) | يحصل أو يضبط قيمة إزاحة الأسطر اللاحقة. إذا تم ضبطها على قيمة غير صفرية، فإن لها ميزة على قيمة FormattingOptions.SubsequentLinesIndent. |
| [getFormattingOptions](#getFormattingOptions--) | يحصل على خيارات التنسيق. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | يحصل على المحاذاة الأفقية للنص داخل مستطيل الفقرة. HorizontalAlignment.None يساوي HorizontalAlignment.Left. |
| [getHyphenSymbol](#getHyphenSymbol--) | يحصل على رمز الواصلة المستخدم في عملية التجزئة. رمز التجزئة هو "-" بشكل افتراضي. لإلغاء رسم الواصلة (مع بقاء عملية الالتفاف) يرجى ضبط سلسلة فارغة string.Empty لخاصية HyphenSymbol. |
| [getMargin](#getMargin--) | يحصل على الحشو. |
| [getPosition](#getPosition--) | يحصل على موضع الفقرة. |
| [getRectangle](#getRectangle--) | يحصل على مستطيل الفقرة. |
| [getRotation](#getRotation--) | يحصل أو يضبط زاوية الدوران بالدرجات. |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | يحصل على قيمة إزاحة الأسطر اللاحقة. |
| [getTextRectangle](#getTextRectangle--) | يحصل على مستطيل النص الموضوع في الفقرة. |
| [getVerticalAlignment](#getVerticalAlignment--) | <p> يحصل على المحاذاة العمودية للنص داخل {@code Rectangle} الخاص بالفقرة. </p> |
| [isJustify](#isJustify--) | يحصل على قيمة ما إذا كان النص مبررًا. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | يضبط لون الخلفية للفقرة النصية. |
| [setBackgroundMode](#setBackgroundMode-int-) | يضبط وضع الخلفية للفقرة النصية |
| [setFirstLineIndent](#setFirstLineIndent-float-) | يحصل أو يضبط قيمة إزاحة الأسطر اللاحقة. إذا تم ضبطها على قيمة غير صفرية، فإن لها ميزة على قيمة FormattingOptions.SubsequentLinesIndent. |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | يضبط خيارات التنسيق. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | يضبط المحاذاة الأفقية للنص داخل مستطيل الفقرة. HorizontalAlignment.None يساوي HorizontalAlignment.Left. |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | يضبط رمز الواصلة المستخدم في عملية التجزئة. رمز التجزئة هو "-" بشكل افتراضي. لإلغاء رسم الواصلة (مع بقاء عملية الالتفاف) يرجى ضبط سلسلة فارغة string.Empty لخاصية HyphenSymbol. |
| [setJustify](#setJustify-boolean-) | يضبط قيمة ما إذا كان النص مبررًا. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | يضبط الحشو. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | يضبط دوران الفقرة. |
| [setOldCodeCompatibilityMode](#setOldCodeCompatibilityMode-boolean-) | يضبط وضع التوافق مع الكود القديم |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | يضبط موضع الفقرة. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | يضبط مستطيل الفقرة. |
| [setRotation](#setRotation-double-) | يحصل أو يضبط زاوية الدوران بالدرجات. |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | يضبط قيمة إزاحة الأسطر اللاحقة. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | يضبط المحاذاة العمودية للنص داخل {@code Rectangle} الخاص بالفقرة. VerticalAlignment.None يساوي VerticalAlignment.Bottom. |

### TextParagraph {#TextParagraph--}
```
public TextParagraph()
```

ينشئ كائن {@code TextParagraph}.

### appendLine {#appendLine-java.lang.String-}
يلحق سطر نص

### appendLine {#appendLine-java.lang.String-float-}
يلحق سطر نص.

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-}
يلحق سطر نص مع معلمات حالة النص.

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-float-}
يلحق سطر نص مع معلمات حالة النص.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-}
يلحق سطر نص مع معلمات حالة النص.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-}
يلحق سطر نص مع معلمات حالة النص.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-}
يلحق سطر نص مع معلمات حالة النص.

### beginEdit {#beginEdit--}
```
public void beginEdit()
```

يبدأ تحرير TextParagraph. <p> يحسن أداء تعبئة TextParagraph. يتم تعليق أي حساب تخطيط حتى يتم استدعاء طريقة EndEdit. <p> لاحظ أن استدعاء الطريقة لا يمكن أن يكون متداخلًا. </p>

### endEdit {#endEdit--}
```
public void endEdit()
```

ينهي تحرير TextParagraph. <p> يحسن أداء تعبئة TextParagraph. يتم تعليق أي حساب تخطيط حتى يتم استدعاء طريقة EndEdit. <p> لاحظ أن استدعاء الطريقة لا يمكن أن يكون متداخلًا. </p>

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

يحصل أو يضبط قيمة إزاحة الأسطر اللاحقة. إذا تم ضبطها على قيمة غير صفرية، فإن لها ميزة على قيمة FormattingOptions.SubsequentLinesIndent.

**Returns:**
قيمة عائمة

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

يحصل على خيارات التنسيق.

**Returns:**
كائن TextFormattingOptions

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

يحصل على المحاذاة الأفقية للنص داخل مستطيل الفقرة. HorizontalAlignment.None يساوي HorizontalAlignment.Left.

**Returns:**
قيمة HorizontalAlignment @see HorizontalAlignment

### getHyphenSymbol {#getHyphenSymbol--}
```
public String getHyphenSymbol()
```

يحصل على رمز الواصلة المستخدم في عملية التجزئة. رمز التجزئة هو "-" بشكل افتراضي. لإلغاء رسم الواصلة (مع بقاء عملية الالتفاف) يرجى ضبط سلسلة فارغة string.Empty لخاصية HyphenSymbol.

**Returns:**
قيمة سلسلة

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

يحصل على الحشو.

**Returns:**
قيمة MarginInfo

### getPosition {#getPosition--}
```
public Position getPosition()
```

يحصل على موضع الفقرة.

**Returns:**
قيمة الموضع

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

يحصل على مستطيل الفقرة.

**Returns:**
كائن Rectangle

### getRotation {#getRotation--}
```
public double getRotation()
```

يحصل أو يضبط زاوية الدوران بالدرجات.

**Returns:**
قيمة double

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

يحصل على قيمة إزاحة الأسطر اللاحقة.

**Returns:**
قيمة عائمة

### getTextRectangle {#getTextRectangle--}
```
public Rectangle getTextRectangle()
```

يحصل على مستطيل النص الموضوع في الفقرة.

**Returns:**
كائن Rectangle

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

<p> يحصل على المحاذاة العمودية للنص داخل {@code Rectangle} الخاص بالفقرة. </p>

**Returns:**
قيمة VerticalAlignment @see VerticalAlignment <hr> <p> VerticalAlignment.None is equal to VerticalAlignment.Bottom. </p>

### isJustify {#isJustify--}
```
public boolean isJustify()
```

يحصل على قيمة ما إذا كان النص مبررًا.

**Returns:**
قيمة منطقية

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
يضبط لون الخلفية للفقرة النصية.

### setBackgroundMode {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```

يضبط وضع الخلفية للفقرة النصية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int @see TextBackgroundMode |

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

يحصل أو يضبط قيمة إزاحة الأسطر اللاحقة. إذا تم ضبطها على قيمة غير صفرية، فإن لها ميزة على قيمة FormattingOptions.SubsequentLinesIndent.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
يضبط خيارات التنسيق.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
يضبط المحاذاة الأفقية للنص داخل مستطيل الفقرة. HorizontalAlignment.None يساوي HorizontalAlignment.Left.

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
يضبط رمز الواصلة المستخدم في عملية التجزئة. رمز التجزئة هو "-" بشكل افتراضي. لإلغاء رسم الواصلة (مع بقاء عملية الالتفاف) يرجى ضبط سلسلة فارغة string.Empty لخاصية HyphenSymbol.

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

يضبط قيمة ما إذا كان النص مبررًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
يضبط الحشو.

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
يضبط دوران الفقرة.

### setOldCodeCompatibilityMode {#setOldCodeCompatibilityMode-boolean-}
```
public void setOldCodeCompatibilityMode(boolean value)
```

يضبط وضع التوافق مع الكود القديم

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setPosition {#setPosition-com.aspose.pdf.Position-}
يضبط موضع الفقرة.

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
يضبط مستطيل الفقرة.

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

يحصل أو يضبط زاوية الدوران بالدرجات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

يضبط قيمة إزاحة الأسطر اللاحقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
يضبط المحاذاة العمودية للنص داخل {@code Rectangle} الخاص بالفقرة. VerticalAlignment.None يساوي VerticalAlignment.Bottom.
