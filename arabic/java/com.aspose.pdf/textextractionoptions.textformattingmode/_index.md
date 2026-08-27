---
title: "TextExtractionOptions.TextFormattingMode"
linktitle: "TextExtractionOptions.TextFormattingMode"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يحدد أوضاعًا مختلفة يمكن استخدامها أثناء تحويل مستند PDF إلى نص. راجع فئة {@code TextDevice}."
type: docs
weight: 5070
url: /ar/java/com.aspose.pdf/textextractionoptions.textformattingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.Enum, com.aspose.pdf.TextExtractionOptions.TextFormattingMode

```
public static final class TextExtractionOptions.TextFormattingMode extends com.aspose.ms.System.Enum
```

يحدد أوضاعًا مختلفة يمكن استخدامها أثناء تحويل مستند PDF إلى نص. راجع فئة {@code TextDevice}.

## الحقول

| حقل | الوصف |
| --- | --- |
| [Flatten](#Flatten) | تمثيل محتوى PDF باستخدام تجزئات النص المتموضع حسب إحداثياتها. هو أساسًا مشابه لوضع "Raw". لكن بينما يركز "Raw" على الحفاظ على بنية تجزئات النص (العوامل) في المستند، يركز "Flatten" على إبقاء النص بالترتيب الذي يُقرأ به. |
| [MemorySaving](#MemorySaving) | استخراج مع توفير الذاكرة. هو تقريبًا نفس وضع 'Raw' لكنه يعمل أسرع قليلًا ويستخدم ذاكرة أقل. |
| [Pure](#Pure) | تمثيل محتوى PDF مع قليل من روتينات التنسيق. |
| [Raw](#Raw) | تمثيل محتوى PDF كما هو، أي بدون تنسيق. |

### Flatten {#Flatten}
```
public static final int Flatten
```

تمثيل محتوى PDF باستخدام تجزئات النص المتموضع حسب إحداثياتها. هو أساسًا مشابه لوضع "Raw". لكن بينما يركز "Raw" على الحفاظ على بنية تجزئات النص (العوامل) في المستند، يركز "Flatten" على إبقاء النص بالترتيب الذي يُقرأ به.

### MemorySaving {#MemorySaving}
```
public static final int MemorySaving
```

استخراج مع توفير الذاكرة. هو تقريبًا نفس وضع 'Raw' لكنه يعمل أسرع قليلًا ويستخدم ذاكرة أقل.

### Pure {#Pure}
```
public static final int Pure
```

تمثيل محتوى PDF مع قليل من روتينات التنسيق.

### Raw {#Raw}
```
public static final int Raw
```

تمثيل محتوى PDF كما هو، أي بدون تنسيق.
