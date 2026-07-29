---
title: "الفئة PsSaveOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.PsSaveOptions. خيارات الحفظ للتصدير إلى تنسيق PS PostScript أو EPS."
type: docs
weight: 9890
url: /ar/net/aspose.pdf/pssaveoptions/
---
## PsSaveOptions class

خيارات الحفظ للتصدير إلى تنسيق PS (PostScript) أو EPS.

```csharp
public class PsSaveOptions : UnifiedSaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PsSaveOptions](pssaveoptions/#constructor)() | منشئ. |
| [PsSaveOptions](pssaveoptions/#constructor_1)(SaveFormat) | منشئ. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا سيتم تخزين رموز الخط في الذاكرة المؤقتة أثناء إعداد صفحات aps. يحسن أداء تحويل PDF إلى صيغ أخرى لكنه يزيد من استهلاك الذاكرة. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا سيتم إغلاق كائن Response بعد حفظ المستند في الاستجابة. |
| [EmbedFont](../../aspose.pdf/pssaveoptions/embedfont/) { get; set; } | يحصل/يعيّن العلامة التي تشير إلى ما إذا كان يجب تضمين الخطوط في مستند PS الناتج. |
| [EmbedFontAs](../../aspose.pdf/pssaveoptions/embedfontas/) { get; set; } | يحصل/يضبط النوع الذي يجب تضمين الخطوط فيه في مستند PS الناتج. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | هذا السمة تفعّل وظيفة استخراج الصورة أو النص لمستندات PDF مع طبقة OCR الفرعية. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | تنسيق حفظ البيانات. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | استدعاء رد نداء لمعالجة أي تحذيرات تم إنشاؤها. يُعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك قد يُعيد المستخدم Abort وفي هذه الحالة يجب إيقاف عملية الحفظ. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | معالجة الصفحات في عدة خيوط. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | أحيانًا تحتوي ملفات PDF على صور خلفية (للصفحات أو خلايا الجداول) مُنشأة من عدة صور خلفية مكررة موضوعة بجانب بعضها. في هذه الحالة قد يولد مُعالج صيغ الهدف (مثل MsWord لتنسيق DOCS) حدودًا مرئية بين أجزاء صور الخلفية، بسبب اختلاف تقنياته في تنعيم حواف الصورة (مضاد التعرج) عن Acrobat Reader. إذا بدا أن المستند المُصدّر يحتوي على مثل هذه الحدود المرئية بين أجزاء صور الخلفية المتشابهة، يرجى تجربة استخدام هذا الإعداد للتخلص من هذا التأثير غير المرغوب. انتباه! عادةً ما تُبطئ هذه تحسين الجودة عملية التحويل بشكل ملحوظ، لذا يرجى استخدام هذا الخيار فقط عندما يكون ضروريًا حقًا. |

### انظر أيضًا

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


