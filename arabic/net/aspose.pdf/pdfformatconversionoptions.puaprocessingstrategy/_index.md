---
title: Enum PdfFormatConversionOptions.PuaProcessingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfFormatConversionOptionsPuaProcessingStrategy enum. بعض مستندات PDF تحتوي على رموز يونيكود خاصة تنتمي إلى منطقة الاستخدام الخاص PUA انظر الوصف في https//en.wikipedia.org/wiki/Private_Use_Areas. هذه الرموز تسبب أخطاء تتوافق مع PDF/A مثل "النص مرتبط بمنطقة الاستخدام الخاص يونيكود ولكن لا يوجد إدخال ActualText". هذه التعداد يعلن عن استراتيجيات يمكن استخدامها للتعامل مع رموز PUA
type: docs
weight: 8390
url: /ar/net/aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy/
---
## PdfFormatConversionOptions.PuaProcessingStrategy enumeration

بعض مستندات PDF تحتوي على رموز يونيكود خاصة، والتي تنتمي إلى منطقة الاستخدام الخاص (PUA)، انظر الوصف في https://en.wikipedia.org/wiki/Private_Use_Areas. هذه الرموز تسبب أخطاء تتوافق مع PDF/A مثل "النص مرتبط بمنطقة الاستخدام الخاص يونيكود ولكن لا يوجد إدخال ActualText". هذه التعداد يعلن عن استراتيجيات يمكن استخدامها للتعامل مع رموز PUA.

```csharp
public enum PuaProcessingStrategy
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | تعطيل معالجة رموز PUA. تُستخدم هذه الاستراتيجية بشكل افتراضي لمستندات PDF/A التي تتوافق مع المستوى B. |
| SurroundPuaTextWithEmptyActualText | `1` | إدراج كتلة محتوى محددة مع إدخال ActualText يحتوي على نص فارغ. تعطي هذه الاستراتيجية نتائج جيدة للمستندات التي لا تحتوي على كتل محتوى محددة. تُستخدم بشكل افتراضي لمستندات PDF/A التي تتوافق مع المستوى A. |
| SubstitutePuaSymbols | `2` | تعمل هذه الاستراتيجية بشكل أبطأ من 'SurroundPuaTextWithEmptyActualText' ولكن يمكنها إزالة الأخطاء المتوافقة مع PUA للمستندات التي لا يمكن التعامل معها بشكل صحيح بواسطة SurroundPuaTextWithEmptyActualText. يتم استبدال رموز PUA برمز 'فراغ' أو يونيكود خاص (بعض رموز PUA لها نظائر يونيكود). يتم تطبيق الاستبدال ليس على نص المستند ولكن على البيانات الداخلية للخط ToUnicode لذا فإنه لا يؤثر على رؤية الرمز ولكن يؤثر على تقديم الرمز في نظام الحافظة لعمليات النسخ/اللصق. |

### See Also

* class [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)