---
title: Class PsSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.PsSaveOptions. خيارات الحفظ للتصدير إلى تنسيق PS PostScript أو EPS
type: docs
weight: 9740
url: /ar/net/aspose.pdf/pssaveoptions/
---
## PsSaveOptions class

خيارات الحفظ للتصدير إلى تنسيق PS (PostScript) أو EPS.

```csharp
public class PsSaveOptions : UnifiedSaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PsSaveOptions](pssaveoptions/#constructor)() | المُنشئ. |
| [PsSaveOptions](pssaveoptions/#constructor_1)(SaveFormat) | المُنشئ. |

## Properties

| Name | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | يحصل أو يحدد قيمة منطقية تشير إلى ما إذا كان سيتم تخزين رموز الخطوط أثناء إعداد صفحات aps. يحسن أداء تحويل PDF إلى تنسيقات أخرى ولكنه يزيد من استهلاك الذاكرة. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | يحصل أو يحدد قيمة منطقية تشير إلى ما إذا كان سيتم إغلاق كائن الاستجابة بعد حفظ المستند في الاستجابة. |
| [EmbedFont](../../aspose.pdf/pssaveoptions/embedfont/) { get; set; } | يحصل/يحدد علامة تشير إلى ما إذا كان يجب تضمين الخطوط في مستند PS الناتج. |
| [EmbedFontAs](../../aspose.pdf/pssaveoptions/embedfontas/) { get; set; } | يحصل/يحدد النوع الذي يجب أن يتم تضمين الخطوط به في مستند PS الناتج. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | هذه السمة تفعيل الوظيفة لاستخراج الصورة أو النص لمستندات PDF مع طبقة OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | تنسيق حفظ البيانات. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | رد الاتصال لمعالجة أي تحذيرات تم إنشاؤها. يُرجع WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك يمكن للمستخدم أيضًا إرجاع Abort وفي هذه الحالة يجب أن تتوقف عملية الحفظ. |

## Fields

| Name | Description |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | معالجة الصفحات في عدة خيوط. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | أحيانًا تحتوي ملفات PDF على صور خلفية (للصفحات أو خلايا الجدول) تم إنشاؤها من عدة صور خلفية متطابقة موضوعة بجانب بعضها البعض. في هذه الحالة، تقوم محركات تنسيقات الهدف (مثل MsWord لتنسيق DOCS) أحيانًا بإنشاء حدود مرئية بين أجزاء الصور الخلفية، لأن تقنياتهم في تنعيم حواف الصور (مضاد التعرج) تختلف عن Acrobat Reader. إذا بدا أن المستند المصدر يحتوي على مثل هذه الحدود المرئية بين أجزاء من نفس الصور الخلفية، يرجى محاولة استخدام هذا الإعداد للتخلص من هذا التأثير غير المرغوب فيه. انتبه! عادةً ما تؤدي هذه التحسينات في الجودة إلى إبطاء التحويل بشكل كبير، لذا، يرجى استخدام هذا الخيار فقط عندما يكون ذلك ضروريًا حقًا. |

### See Also

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)