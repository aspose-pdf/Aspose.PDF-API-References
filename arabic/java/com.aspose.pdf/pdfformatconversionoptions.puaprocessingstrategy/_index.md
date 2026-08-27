---
title: "PdfFormatConversionOptions.PuaProcessingStrategy"
linktitle: "PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "بعض مستندات PDF تحتوي على رموز يونيكود خاصة، والتي تنتمي إلى منطقة الاستخدام الخاص (PUA)، راجع الوصف على https://en.wikipedia.org/wiki/Private_Use_Areas. هذه الرموز."
type: docs
weight: 3750
url: /ar/java/com.aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.PuaProcessingStrategy

```
public static final class PdfFormatConversionOptions.PuaProcessingStrategy extends com.aspose.ms.System.Enum
```

بعض مستندات PDF تحتوي على رموز يونيكود خاصة، تنتمي إلى منطقة الاستخدام الخاص (PUA)، راجع الوصف على https://en.wikipedia.org/wiki/Private_Use_Areas. هذه الرموز تتسبب في أخطاء توافق مع PDF/A مثل "Text is mapped to Unicode Private Use Area but no ActualText entry is present". هذا التعداد يعلن استراتيجيات يمكن استخدامها لمعالجة رموز PUA.

## الحقول

| حقل | الوصف |
| --- | --- |
| [None](#None) | تعطيل معالجة رموز PUA. تُستخدم هذه الإستراتيجية بشكل افتراضي لمستندات PDF/A ذات توافق المستوى B. |
| [SubstitutePuaSymbols](#SubstitutePuaSymbols) | تعمل هذه الإستراتيجية ببطء أكثر من 'SurroundPuaTextWithEmptyActualText' لكنها يمكنها إزالة الأخطاء المتوافقة مع PUA للمستندات التي لا يمكن معالجتها بشكل صحيح بواسطة SurroundPuaTextWithEmptyActualText. يتم استبدال رموز PUA بالرمز 'space' أو يونيكود خاص (بعض رموز PUA لها نظائر يونيكود). يتم تطبيق الاستبدال ليس على نص المستند بل على البيانات الداخلية للخط ToUnicode، لذا لا يؤثر على رؤية الرمز لكنه يؤثر على عرض الرمز في عملية النسخ/اللصق في ذاكرة النظام. |
| [SurroundPuaTextWithEmptyActualText](#SurroundPuaTextWithEmptyActualText) | يدرج كتلة محتوى معلمة مع إدخال ActualText يحتوي على نص فارغ. تُعطي هذه الإستراتيجية نتائج جيدة للمستندات التي لا تحتوي على كتل محتوى معلمة. تُستخدم بشكل افتراضي لمستندات PDF/A ذات توافق المستوى A. |

### None {#None}
```
public static final int None
```

تعطيل معالجة رموز PUA. تُستخدم هذه الإستراتيجية بشكل افتراضي لمستندات PDF/A ذات توافق المستوى B.

### SubstitutePuaSymbols {#SubstitutePuaSymbols}
```
public static final int SubstitutePuaSymbols
```

تعمل هذه الإستراتيجية ببطء أكثر من 'SurroundPuaTextWithEmptyActualText' لكنها يمكنها إزالة الأخطاء المتوافقة مع PUA للمستندات التي لا يمكن معالجتها بشكل صحيح بواسطة SurroundPuaTextWithEmptyActualText. يتم استبدال رموز PUA بالرمز 'space' أو يونيكود خاص (بعض رموز PUA لها نظائر يونيكود). يتم تطبيق الاستبدال ليس على نص المستند بل على البيانات الداخلية للخط ToUnicode، لذا لا يؤثر على رؤية الرمز لكنه يؤثر على عرض الرمز في عملية النسخ/اللصق في ذاكرة النظام.

### SurroundPuaTextWithEmptyActualText {#SurroundPuaTextWithEmptyActualText}
```
public static final int SurroundPuaTextWithEmptyActualText
```

يدرج كتلة محتوى معلمة مع إدخال ActualText يحتوي على نص فارغ. تُعطي هذه الإستراتيجية نتائج جيدة للمستندات التي لا تحتوي على كتل محتوى معلمة. تُستخدم بشكل افتراضي لمستندات PDF/A ذات توافق المستوى A.
