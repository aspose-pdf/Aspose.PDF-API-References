---
title: MobiXmlSaveOptions
second_title: Aspose.PDF لمرجع .NET API
description: حفظ الخيارات للتصدير إلى تنسيق Xml
type: docs
weight: 4800
url: /ar/net/aspose.pdf/mobixmlsaveoptions/
---
## MobiXmlSaveOptions class

حفظ الخيارات للتصدير إلى تنسيق Xml

```csharp
public class MobiXmlSaveOptions : UnifiedSaveOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [MobiXmlSaveOptions](mobixmlsaveoptions)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | الحصول على أو تعيين قيمة منطقية تشير إلى أنه سيتم إغلاق كائن الاستجابة بعد حفظ المستند في الاستجابة. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly) { get; set; } | هذا السمة شغّل وظيفة استخراج صورة أو نص لمستندات PDF ذات الطبقة الفرعية OCR . |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | تنسيق حفظ البيانات . |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | رد الاتصال للتعامل مع أي تحذيرات تم إنشاؤها. يقوم WarningHandler بإرجاع عنصر التعداد ReturnAction الذي يحدد إما متابعة أو إحباط. متابعة هو الإجراء الافتراضي وتستمر عملية "حفظ" ، ومع ذلك قد يقوم المستخدم أيضًا بإرجاع "إحباط" وفي هذه الحالة يجب أن تتوقف عملية "حفظ". |

## مجالات

| اسم | وصف |
| --- | --- |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages) | في بعض الأحيان تحتوي ملفات PDF على صور خلفية (لصفحات أو خلايا جدول) تم إنشاؤها من عدة صور خلفية متشابهة ، ضع واحدة بالقرب من الأخرى. في مثل هذه الحالة ، تنشئ عارضات التنسيقات المستهدفة (fe MsWord لتنسيق DOCS) أحيانًا حدودًا مرئية بين أجزاء من صور الخلفية ، لأن تقنيات تجانس حافة الصورة (الصقل) تختلف عن Acrobat Reader . إذا بدا أن المستند المُصدَّر يحتوي على حدود مرئية بين أجزاء من نفس صور الخلفية ، يرجى محاولة استخدام هذا الإعداد للتخلص من من ذلك تأثير غير مرغوب فيه. انتبه! عادةً ما يؤدي هذا التحسين للجودة إلى إبطاء عملية التحويل ، لذا ، من فضلك ، استخدم هذا الخيار فقط عندما يكون ضروريًا حقًا. |

### أنظر أيضا

* class [UnifiedSaveOptions](../unifiedsaveoptions)
* مساحة الاسم [Aspose.Pdf](../../aspose.pdf)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->