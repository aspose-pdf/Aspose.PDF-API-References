---
title: "SimpleFontSubstitution"
linktitle: "SimpleFontSubstitution"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة لاستراتيجية استبدال الخطوط البسيطة."
type: docs
weight: 90
url: /ar/java/com.aspose.pdf.text/simplefontsubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SimpleFontSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SimpleFontSubstitution

```
public final class SimpleFontSubstitution extends FontSubstitution
```

يمثل فئة لاستراتيجية استبدال الخطوط البسيطة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SimpleFontSubstitution](#SimpleFontSubstitution-java.lang.String-java.lang.String-) | ينشئ مثيلاً جديداً من الفئة {@code SimpleFontSubstitution}. |
| [SimpleFontSubstitution](#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-) | ينشئ مثيلاً جديداً من الفئة {@code SimpleFontSubstitution}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | يحصل على اسم الخط الأصلي الذي يجب استبداله بـ {@code SubstitutionFontName} |
| [getSubstitutedUnicode](#getSubstitutedUnicode-char-) | يعيد استبدال unicode |
| [getSubstitutionFontName](#getSubstitutionFontName--) | يحصل على اسم الخط الذي يجب أن يحل محل {@code OriginalFontName} |

### SimpleFontSubstitution {#SimpleFontSubstitution-java.lang.String-java.lang.String-}
ينشئ مثيلاً جديداً من الفئة {@code SimpleFontSubstitution}.

### SimpleFontSubstitution {#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-}
ينشئ مثيلاً جديداً من الفئة {@code SimpleFontSubstitution}.

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

يحصل على اسم الخط الأصلي الذي يجب استبداله بـ {@code SubstitutionFontName}

**Returns:**
قيمة سلسلة

### getSubstitutedUnicode {#getSubstitutedUnicode-char-}
```
public char getSubstitutedUnicode(char unicode)
```

يعيد استبدال unicode

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| unicode |  | قيمة char |

**Returns:**
قيمة char

### getSubstitutionFontName {#getSubstitutionFontName--}
```
public String getSubstitutionFontName()
```

يحصل على اسم الخط الذي يجب أن يحل محل {@code OriginalFontName}

**Returns:**
قيمة سلسلة
