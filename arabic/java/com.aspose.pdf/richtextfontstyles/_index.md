---
title: "RichTextFontStyles"
linktitle: "RichTextFontStyles"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "خيارات تنسيق مقاطع النص في RichText."
type: docs
weight: 4300
url: /ar/java/com.aspose.pdf/richtextfontstyles/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.Enum, com.aspose.pdf.RichTextFontStyles

```
public final class RichTextFontStyles extends com.aspose.ms.System.Enum
```

خيارات تنسيق مقاطع النص في RichText.

## الحقول

| حقل | الوصف |
| --- | --- |
| [Bold](#Bold) | خيار يحدد النص الغامق. |
| [ClearExisting](#ClearExisting) | إذا تم تعيينه، يمسح جميع الأنماط الموجودة قبل تطبيق الأنماط الإضافية. عند الجمع مع علامات نمط أخرى (مثال، {@code RichTextFontStyles#Bold})، يتم أولاً إعادة تعيين الأنماط، ثم تطبيق المحددة. بدون هذه العلامة، تُضاف الأنماط الجديدة إلى الأنماط الحالية. |
| [Italic](#Italic) | خيار يحدد النص المائل. |
| [Underline](#Underline) | خيار يحدد الخط السفلي. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) | يتحقق مما إذا كانت العلامة المحددة مفعلة. |

### Bold {#Bold}
```
public static final int Bold
```

خيار يحدد النص الغامق.

### ClearExisting {#ClearExisting}
```
public static final int ClearExisting
```

إذا تم تعيينه، يمسح جميع الأنماط الموجودة قبل تطبيق الأنماط الإضافية. عند الجمع مع علامات نمط أخرى (مثال، {@code RichTextFontStyles#Bold})، يتم أولاً إعادة تعيين الأنماط، ثم تطبيق المحددة. بدون هذه العلامة، تُضاف الأنماط الجديدة إلى الأنماط الحالية.

### Italic {#Italic}
```
public static final int Italic
```

خيار يحدد النص المائل.

### Underline {#Underline}
```
public static final int Underline
```

خيار يحدد الخط السفلي.

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```

يتحقق مما إذا كانت العلامة المحددة مفعلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| flag |  | قيمة التعداد التي تمثل العلامة المراد فحصها |
| flagToCheck |  | قيمة التعداد التي تمثل العلامة المراد فحصها |

**Returns:**
{@code true} إذا كانت العلامة مفعلة؛ {@code false} خلاف ذلك
