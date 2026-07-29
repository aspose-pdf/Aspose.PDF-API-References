---
title: "TextEditOptions"
linktitle: "TextEditOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يصف خيارات عمليات تحرير النص."
type: docs
weight: 4970
url: /ar/java/com.aspose.pdf/texteditoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextEditOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextEditOptions

```
public final class TextEditOptions extends TextOptions
```

يصف خيارات عمليات تحرير النص.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextEditOptions](#TextEditOptions--) | ينشئ نسخة جديدة من كائن {@code TextEditOptions} مع الخيارات الافتراضية. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-boolean-) | / * / * ينشئ نسخة جديدة من كائن {@code TextEditOptions} للطور المحدد لإعادة ترتيب النص. / * / * |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-) | ينشئ نسخة جديدة من كائن {@code TextEditOptions} مع الخيارات الافتراضية. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | ينشئ نسخة جديدة من كائن {@code TextEditOptions} مع الخيارات الافتراضية. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | ينشئ نسخة جديدة من كائن {@code TextEditOptions} مع الخيارات الافتراضية. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-) | ينشئ نسخة جديدة من كائن {@code TextEditOptions} مع الخيارات الافتراضية. NoCharacterAction.UseStandardFont LanguageTransformation.Default |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAllowLanguageTransformation](#getAllowLanguageTransformation--) | يحصل على القيمة التي تسمح باستخدام تحويل اللغة أثناء إضافة أو تحرير النص. true - سيتم تطبيق تحويل اللغة إذا لزم الأمر (القيمة الافتراضية). false - لن يتم تطبيق تحويل اللغة. |
| [getClippingPathsProcessing](#getClippingPathsProcessing--) | يحصل على الوضع لمعالجة مسار القص للنص المعدل. |
| [getFontReplaceBehavior](#getFontReplaceBehavior--) | يحصل على الوضع الذي يحدد السلوك لسيناريوهات استبدال الخطوط. |
| [getLanguageTransformationBehavior](#getLanguageTransformationBehavior--) | يحصل على الوضع الذي يحدد السلوك لسيناريوهات تحويل اللغة. |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | يحصل على الوضع الذي يحدد السلوك في حال عدم احتواء الخطوط على الأحرف المطلوبة. |
| [getReplacementFont](#getReplacementFont--) | يحصل أو يضبط الخط المستخدم للاستبدال إذا لم يحتوي خط المستخدم على الحرف المطلوب |
| [getToAttemptGetUnderlineFromSource](#getToAttemptGetUnderlineFromSource--) | <p> يحصل أو يضبط القيمة التي تسمح بالبحث عن تسطير النص على صفحة المستند المصدر. <p> (مهمل) يرجى استخدام TextSearchOptions.SearchForTextRelatedGraphics بدلاً من ذلك. </p> |
| [setAllowLanguageTransformation](#setAllowLanguageTransformation-boolean-) | يضبط القيمة التي تسمح باستخدام تحويل اللغة أثناء إضافة أو تحرير النص. true - سيتم تطبيق تحويل اللغة إذا لزم الأمر (القيمة الافتراضية). false - لن يتم تطبيق تحويل اللغة. |
| [setClippingPathsProcessing](#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-) | يحصل على الوضع لمعالجة مسار القص للنص المعدل. |
| [setFontReplaceBehavior](#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-) | يضبط الوضع الذي يحدد السلوك لسيناريوهات استبدال الخطوط. |
| [setLanguageTransformationBehavior](#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | يضبط الوضع الذي يحدد السلوك لسيناريوهات تحويل اللغة. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | يضبط الوضع الذي يحدد السلوك في حال عدم احتواء الخطوط على الأحرف المطلوبة. |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | يحصل أو يضبط الخط المستخدم للاستبدال إذا لم يحتوي خط المستخدم على الحرف المطلوب |
| [setToAttemptGetUnderlineFromSource](#setToAttemptGetUnderlineFromSource-boolean-) | <p> يحصل أو يضبط القيمة التي تسمح بالبحث عن تسطير النص على صفحة المستند المصدر. <p> (مهمل) يرجى استخدام TextSearchOptions.SearchForTextRelatedGraphics بدلاً من ذلك. </p> |

### TextEditOptions {#TextEditOptions--}
```
public TextEditOptions()
```

ينشئ نسخة جديدة من كائن {@code TextEditOptions} مع الخيارات الافتراضية. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-boolean-}
```
public TextEditOptions(boolean allowLanguageTransformation)
```

/ * / * ينشئ نسخة جديدة من كائن {@code TextEditOptions} للطور المحدد لإعادة ترتيب النص. / * / *

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| allowLanguageTransformation |  |  |

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-}
ينشئ نسخة جديدة من كائن {@code TextEditOptions} مع الخيارات الافتراضية. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
ينشئ نسخة جديدة من كائن {@code TextEditOptions} مع الخيارات الافتراضية. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
ينشئ نسخة جديدة من كائن {@code TextEditOptions} مع الخيارات الافتراضية. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-}
ينشئ نسخة جديدة من كائن {@code TextEditOptions} مع الخيارات الافتراضية. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### getAllowLanguageTransformation {#getAllowLanguageTransformation--}
```
public boolean getAllowLanguageTransformation()
```

يحصل على القيمة التي تسمح باستخدام تحويل اللغة أثناء إضافة أو تحرير النص. true - سيتم تطبيق تحويل اللغة إذا لزم الأمر (القيمة الافتراضية). false - لن يتم تطبيق تحويل اللغة.

**Returns:**
قيمة منطقية

### getClippingPathsProcessing {#getClippingPathsProcessing--}
```
public final TextEditOptions.ClippingPathsProcessingMode getClippingPathsProcessing()
```

يحصل على الوضع لمعالجة مسار القص للنص المعدل.

**Returns:**
عنصر ClippingPathsProcessingMode

### getFontReplaceBehavior {#getFontReplaceBehavior--}
```
public TextEditOptions.FontReplace getFontReplaceBehavior()
```

يحصل على الوضع الذي يحدد السلوك لسيناريوهات استبدال الخطوط.

**Returns:**
قيمة FontReplace @see FontReplace

### getLanguageTransformationBehavior {#getLanguageTransformationBehavior--}
```
public TextEditOptions.LanguageTransformation getLanguageTransformationBehavior()
```

يحصل على الوضع الذي يحدد السلوك لسيناريوهات تحويل اللغة.

**Returns:**
قيمة LanguageTransformation @see LanguageTransformation

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public TextEditOptions.NoCharacterAction getNoCharacterBehavior()
```

يحصل على الوضع الذي يحدد السلوك في حال عدم احتواء الخطوط على الأحرف المطلوبة.

**Returns:**
قيمة NoCharacterAction @see NoCharacterAction

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

يحصل أو يضبط الخط المستخدم للاستبدال إذا لم يحتوي خط المستخدم على الحرف المطلوب

**Returns:**
كائن Font

### getToAttemptGetUnderlineFromSource {#getToAttemptGetUnderlineFromSource--}
```
public boolean getToAttemptGetUnderlineFromSource()
```

<p> يحصل أو يضبط القيمة التي تسمح بالبحث عن تسطير النص على صفحة المستند المصدر. <p> (مهمل) يرجى استخدام TextSearchOptions.SearchForTextRelatedGraphics بدلاً من ذلك. </p>

**Returns:**
قيمة منطقية

### setAllowLanguageTransformation {#setAllowLanguageTransformation-boolean-}
```
public void setAllowLanguageTransformation(boolean value)
```

يضبط القيمة التي تسمح باستخدام تحويل اللغة أثناء إضافة أو تحرير النص. true - سيتم تطبيق تحويل اللغة إذا لزم الأمر (القيمة الافتراضية). false - لن يتم تطبيق تحويل اللغة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setClippingPathsProcessing {#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-}
يحصل على الوضع لمعالجة مسار القص للنص المعدل.

### setFontReplaceBehavior {#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-}
يضبط الوضع الذي يحدد السلوك لسيناريوهات استبدال الخطوط.

### setLanguageTransformationBehavior {#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
يضبط الوضع الذي يحدد السلوك لسيناريوهات تحويل اللغة.

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
يضبط الوضع الذي يحدد السلوك في حال عدم احتواء الخطوط على الأحرف المطلوبة.

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
يحصل أو يضبط الخط المستخدم للاستبدال إذا لم يحتوي خط المستخدم على الحرف المطلوب

### setToAttemptGetUnderlineFromSource {#setToAttemptGetUnderlineFromSource-boolean-}
```
public void setToAttemptGetUnderlineFromSource(boolean value)
```

<p> يحصل أو يضبط القيمة التي تسمح بالبحث عن تسطير النص على صفحة المستند المصدر. <p> (مهمل) يرجى استخدام TextSearchOptions.SearchForTextRelatedGraphics بدلاً من ذلك. </p>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
