---
title: Class UnifiedSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.UnifiedSaveOptions. تمثل هذه الفئة خيارات الحفظ للحفظ الذي يستخدم طريقة تحويل موحدة مع نموذج مستند داخلي موحد
type: docs
weight: 11140
url: /ar/net/aspose.pdf/unifiedsaveoptions/
---
## فئة UnifiedSaveOptions

تمثل هذه الفئة خيارات الحفظ للحفظ الذي يستخدم طريقة تحويل موحدة (مع نموذج مستند داخلي موحد)

```csharp
public class UnifiedSaveOptions : SaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [UnifiedSaveOptions](unifiedsaveoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | يحصل أو يحدد قيمة منطقية تشير إلى ما إذا كانت رموز الخطوط ستُخزن أثناء إعداد صفحات aps. يحسن أداء تحويل PDF إلى تنسيقات أخرى ولكنه يزيد من استهلاك الذاكرة. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | يحصل أو يحدد قيمة منطقية تشير إلى ما إذا كان سيتم إغلاق كائن الاستجابة بعد حفظ المستند في الاستجابة. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | هذه السمة تفعيل وظيفة استخراج الصورة أو النص لمستندات PDF مع طبقة فرعية OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | تنسيق حفظ البيانات. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | رد نداء لمعالجة أي تحذيرات تم إنشاؤها. يعيد WarningHandler عنصر تعداد ReturnAction يحدد إما الاستمرار أو الإنهاء. الاستمرار هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك يمكن للمستخدم أيضًا إعادة الإنهاء، وفي هذه الحالة يجب أن تتوقف عملية الحفظ. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | معالجة الصفحات في عدة خيوط. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | أحيانًا تحتوي ملفات PDF على صور خلفية (للصفحات أو خلايا الجدول) تم إنشاؤها من عدة صور خلفية متكررة موضوعة بجانب بعضها البعض. في هذه الحالة، تقوم محركات التنسيق المستهدفة (مثل MsWord لتنسيق DOCS) أحيانًا بإنشاء حدود مرئية بين أجزاء الصور الخلفية، لأن تقنياتهم في تنعيم حواف الصور (مضاد التعرج) تختلف عن Acrobat Reader. إذا بدا أن المستند المصدر يحتوي على مثل هذه الحدود المرئية بين أجزاء الصور الخلفية نفسها، يرجى محاولة استخدام هذا الإعداد للتخلص من هذا التأثير غير المرغوب فيه. انتبه! عادةً ما تؤدي هذه التحسينات في الجودة إلى إبطاء التحويل بشكل كبير، لذا، يرجى استخدام هذا الخيار فقط عند الضرورة. |

### انظر أيضًا

* فئة [SaveOptions](../saveoptions/)
* مساحة [Aspose.Pdf](../../aspose.pdf/)
* تجميع [Aspose.PDF](../../)