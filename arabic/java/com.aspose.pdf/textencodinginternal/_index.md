---
title: "TextEncodingInternal"
linktitle: "TextEncodingInternal"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description:
type: docs
weight: 5030
url: /ar/java/com.aspose.pdf/textencodinginternal/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextEncodingInternal

```
public final class TextEncodingInternal extends Object
```



## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextEncodingInternal](#TextEncodingInternal-com.aspose.ms.System.Text.Encoding-) | منشئ داخلي |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getASCII](#getASCII--) | يحصل على ترميز لمجموعة الأحرف ASCII (7 بت). |
| [getBigEndianUnicode](#getBigEndianUnicode--) | يحصل على ترميز لتنسيق UTF-16 الذي يستخدم ترتيب البايتات كبير النهاية. |
| [getDefault](#getDefault--) | يحصل على ترميز لصفحة الرموز ANSI الحالية لنظام التشغيل. |
| [getEncoding](#getEncoding-java.lang.String-) | يعيد الترميز المرتبط باسم صفحة الرموز المحدد. |
| [getInternalFormat](#getInternalFormat--) | طريقة داخلية |
| [getNames](#getNames--) | يحصل على مصفوفة بأسماء الترميزات. |
| [getString](#getString-byte:A-) | عند تجاوزها في فئة مشتقة، تقوم بفك تشفير جميع البايتات في مصفوفة البايتات المحددة إلى سلسلة. |
| [getUnicode](#getUnicode--) | يحصل على ترميز لتنسيق UTF-16 باستخدام ترتيب البايتات صغير النهاية. |
| [getUTF32](#getUTF32--) | يحصل على ترميز لتنسيق UTF-32 باستخدام ترتيب البايتات صغير النهاية. |
| [getUTF32BE](#getUTF32BE--) | يحصل على ترميز لتنسيق UTF-16 الذي يستخدم ترتيب البايتات كبير النهاية. |
| [getUTF7](#getUTF7--) | يحصل على ترميز لتنسيق UTF-7. |
| [getUTF8](#getUTF8--) | يحصل على ترميز لتنسيق UTF-8. |
| [getUTF8Unmarked](#getUTF8Unmarked--) | يحصل على ترميز لتنسيق UTF-8 غير المعلم. |
| [toString](#toString-com.aspose.pdf.TextEncodingInternal-) | يعيد سلسلة تمثل الكائن الحالي. |

### TextEncodingInternal {#TextEncodingInternal-com.aspose.ms.System.Text.Encoding-}
منشئ داخلي

### getASCII {#getASCII--}
```
public static TextEncodingInternal getASCII()
```

يحصل على ترميز لمجموعة الأحرف ASCII (7 بت).

**Returns:**
مثيل TextEncodingInternal

### getBigEndianUnicode {#getBigEndianUnicode--}
```
public static TextEncodingInternal getBigEndianUnicode()
```

يحصل على ترميز لتنسيق UTF-16 الذي يستخدم ترتيب البايتات كبير النهاية.

**Returns:**
مثيل TextEncodingInternal

### getDefault {#getDefault--}
```
public static TextEncodingInternal getDefault()
```

يحصل على ترميز لصفحة الرموز ANSI الحالية لنظام التشغيل.

**Returns:**
مثيل TextEncodingInternal

### getEncoding {#getEncoding-java.lang.String-}
يعيد الترميز المرتبط باسم صفحة الرموز المحدد.

### getInternalFormat {#getInternalFormat--}
```
public com.aspose.ms.System.Text.Encoding getInternalFormat()
```

طريقة داخلية

**Returns:**
كائن داخلي

### getNames {#getNames--}
```
public static String [] getNames()
```

يحصل على مصفوفة بأسماء الترميزات.

**Returns:**
مصفوفة سلاسل

### getString {#getString-byte:A-}
```
public String getString(byte[] value)
```

عند تجاوزها في فئة مشتقة، تقوم بفك تشفير جميع البايتات في مصفوفة البايتات المحددة إلى سلسلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | مصفوفة البايتات التي تحتوي على تسلسل البايتات لفك تشفيرها. |

**Returns:**
سلسلة تحتوي على نتائج فك تشفير تسلسل البايتات المحدد.

### getUnicode {#getUnicode--}
```
public static TextEncodingInternal getUnicode()
```

يحصل على ترميز لتنسيق UTF-16 باستخدام ترتيب البايتات صغير النهاية.

**Returns:**
مثيل TextEncodingInternal

### getUTF32 {#getUTF32--}
```
public static TextEncodingInternal getUTF32()
```

يحصل على ترميز لتنسيق UTF-32 باستخدام ترتيب البايتات صغير النهاية.

**Returns:**
مثيل TextEncodingInternal

### getUTF32BE {#getUTF32BE--}
```
public static TextEncodingInternal getUTF32BE()
```

يحصل على ترميز لتنسيق UTF-16 الذي يستخدم ترتيب البايتات كبير النهاية.

**Returns:**
مثيل TextEncodingInternal

### getUTF7 {#getUTF7--}
```
public static TextEncodingInternal getUTF7()
```

يحصل على ترميز لتنسيق UTF-7.

**Returns:**
مثيل TextEncodingInternal

### getUTF8 {#getUTF8--}
```
public static TextEncodingInternal getUTF8()
```

يحصل على ترميز لتنسيق UTF-8.

**Returns:**
مثيل TextEncodingInternal

### getUTF8Unmarked {#getUTF8Unmarked--}
```
public static TextEncodingInternal getUTF8Unmarked()
```

يحصل على ترميز لتنسيق UTF-8 غير المعلم.

**Returns:**
مثيل TextEncodingInternal

### toString {#toString-com.aspose.pdf.TextEncodingInternal-}
يعيد سلسلة تمثل الكائن الحالي.
