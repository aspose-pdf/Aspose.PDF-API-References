---
title: "التعداد PdfFormatConversionOptions.PuaProcessingStrategy"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "التعداد Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy. بعض مستندات PDF تحتوي على رموز يونيكود خاصة تنتمي إلى منطقة الاستخدام الخاص (PUA) راجع الوصف على https//en.wikipedia.org/wiki/Private_Use_Areas. هذه الرموز تسبب أخطاء توافق مع PDF/A مثل أن النص تم تعيينه إلى منطقة الاستخدام الخاص في يونيكود ولكن لا توجد إدخال ActualText. يعلن هذا التعداد عن استراتيجيات يمكن استخدامها لمعالجة رموز PUA"
type: docs
weight: 8530
url: /ar/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## PdfFormatConversionOptions.PuaProcessingStrategy enumeration

بعض مستندات PDF تحتوي على رموز يونيكود خاصة، تنتمي إلى منطقة الاستخدام الخاص (PUA)، راجع الوصف على https://en.wikipedia.org/wiki/Private_Use_Areas. هذه الرموز تسبب أخطاء توافق مع PDF/A مثل "تم تعيين النص إلى منطقة الاستخدام الخاص في يونيكود ولكن لا يوجد إدخال ActualText". يعلن هذا التعداد عن استراتيجيات يمكن استخدامها لمعالجة رموز PUA.

```csharp
public enum PuaProcessingStrategy
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | `0` | تعطيل معالجة رموز PUA. تُستخدم هذه الاستراتيجية افتراضيًا لمستندات PDF/A ذات التوافق المستوى B. |
| SurroundPuaTextWithEmptyActualText | `1` | يدرج كتلة محتوى معلمة مع إدخال ActualText يحتوي على نص فارغ. تُعطي هذه الاستراتيجية نتائج جيدة للمستندات التي لا تحتوي على كتل محتوى معلمة. تُستخدم افتراضيًا لمستندات PDF/A ذات التوافق المستوى A. |
| SubstitutePuaSymbols | `2` | تعمل هذه الاستراتيجية ببطء أكثر من 'SurroundPuaTextWithEmptyActualText' لكنها يمكنها إزالة أخطاء التوافق مع PUA للمستندات التي لا يمكن معالجتها بشكل صحيح بواسطة SurroundPuaTextWithEmptyActualText. يتم استبدال رموز PUA بالرمز 'space' أو يونيكود خاص (بعض رموز PUA لها نظائر يونيكود). يتم تطبيق الاستبدال ليس على نص المستند بل على البيانات الداخلية للخط ToUnicode لذا لا يؤثر على رؤية الرمز لكنه يؤثر على عرض الرمز في عملية النسخ/اللصق في مخزن النظام. |

### انظر أيضًا

* class [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


