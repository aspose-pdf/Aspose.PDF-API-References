---
title: "TextFormattingOptions"
linktitle: "TextFormattingOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل خيارات تنسيق النص"
type: docs
weight: 5080
url: /ar/java/com.aspose.pdf/textformattingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextFormattingOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextFormattingOptions

```
public final class TextFormattingOptions extends TextOptions
```

يمثل خيارات تنسيق النص

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextFormattingOptions](#TextFormattingOptions--) | ينشئ نسخة جديدة من كائن {@code TextFormattingOptions} مع وضع التفاف الكلمات غير معرف. |
| [TextFormattingOptions](#TextFormattingOptions-int-) | ينشئ نسخة جديدة من كائن {@code TextFormattingOptions} للوضع المحدد لتفاف الكلمات. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFirstLineIndent](#getFirstLineIndent--) | يحصل أو يضبط قيمة إزاحة السطر الأول. |
| [getHyphenSymbol](#getHyphenSymbol--) | <p> يحصل أو يحدد رمز الواصلة الذي يُستخدم في عملية التجزئة. </p><hr> لإلغاء رسم الواصلة (مع بقاء إجراء الالتفاف) يرجى تعيين سلسلة فارغة string.Empty لـ HyphenSymbol. |
| [getLineSpacing](#getLineSpacing--) | يحصل على وضع تباعد السطر. القيمة الافتراضية هي LineSpacingMode.FontSize |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | يحصل أو يحدد قيمة إزاحة الأسطر اللاحقة. |
| [getWrapMode](#getWrapMode--) | يحصل على وضع التفاف الكلمات. القيمة الافتراضية هي WordWrapMode.NoWrap |
| [setFirstLineIndent](#setFirstLineIndent-float-) | يحصل أو يضبط قيمة إزاحة السطر الأول. |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | <p> يحصل أو يحدد رمز الواصلة الذي يُستخدم في عملية التجزئة. </p><hr> لإلغاء رسم الواصلة (مع بقاء إجراء الالتفاف) يرجى تعيين سلسلة فارغة string.Empty لـ HyphenSymbol. |
| [setLineSpacing](#setLineSpacing-int-) | يحدد وضع تباعد السطر. القيمة الافتراضية هي LineSpacingMode.FontSize |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | يحصل أو يحدد قيمة إزاحة الأسطر اللاحقة. |
| [setWrapMode](#setWrapMode-int-) | يحدد وضع التفاف الكلمات. القيمة الافتراضية هي WordWrapMode.NoWrap |

### TextFormattingOptions {#TextFormattingOptions--}
```
public TextFormattingOptions()
```

ينشئ نسخة جديدة من كائن {@code TextFormattingOptions} مع وضع التفاف الكلمات غير معرف.

### TextFormattingOptions {#TextFormattingOptions-int-}
```
public TextFormattingOptions(int wrapMode)
```

ينشئ نسخة جديدة من كائن {@code TextFormattingOptions} للوضع المحدد لتفاف الكلمات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| wrapMode |  | وضع التفاف الكلمات. @see WordWrapMode |

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

يحصل أو يضبط قيمة إزاحة السطر الأول.

**Returns:**
قيمة عائمة

### getHyphenSymbol {#getHyphenSymbol--}
```
public final String getHyphenSymbol()
```

<p> يحصل أو يحدد رمز الواصلة الذي يُستخدم في عملية التجزئة. </p><hr> لإلغاء رسم الواصلة (مع بقاء إجراء الالتفاف) يرجى تعيين سلسلة فارغة string.Empty لـ HyphenSymbol.

**Returns:**
قيمة سلسلة

### getLineSpacing {#getLineSpacing--}
```
public int getLineSpacing()
```

يحصل على وضع تباعد السطر. القيمة الافتراضية هي LineSpacingMode.FontSize

**Returns:**
قيمة int @see LineSpacingMode

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

يحصل أو يحدد قيمة إزاحة الأسطر اللاحقة.

**Returns:**
قيمة عائمة

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

يحصل على وضع التفاف الكلمات. القيمة الافتراضية هي WordWrapMode.NoWrap

**Returns:**
قيمة WordWrapMode @see WordWrapMode

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

يحصل أو يضبط قيمة إزاحة السطر الأول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
<p> يحصل أو يحدد رمز الواصلة الذي يُستخدم في عملية التجزئة. </p><hr> لإلغاء رسم الواصلة (مع بقاء إجراء الالتفاف) يرجى تعيين سلسلة فارغة string.Empty لـ HyphenSymbol.

### setLineSpacing {#setLineSpacing-int-}
```
public void setLineSpacing(int value)
```

يحدد وضع تباعد السطر. القيمة الافتراضية هي LineSpacingMode.FontSize

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int @see LineSpacingMode |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

يحصل أو يحدد قيمة إزاحة الأسطر اللاحقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

يحدد وضع التفاف الكلمات. القيمة الافتراضية هي WordWrapMode.NoWrap

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة WordWrapMode @see WordWrapMode |
