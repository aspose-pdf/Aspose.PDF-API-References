---
title: Class PdfXmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.PdfXmlSaveOptions. خيارات الحفظ لتنسيق PdfXml
type: docs
weight: 8470
url: /ar/net/aspose.pdf/pdfxmlsaveoptions/
---
## PdfXmlSaveOptions class

خيارات الحفظ لتنسيق PdfXml.

```csharp
public class PdfXmlSaveOptions : UnifiedSaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfXmlSaveOptions](pdfxmlsaveoptions/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | يحصل أو يحدد قيمة منطقية تشير إلى ما إذا كان سيتم تخزين رموز الخطوط أثناء إعداد صفحات aps. يحسن أداء تحويل PDF إلى تنسيقات أخرى ولكنه يزيد من استهلاك الذاكرة. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | يحصل أو يحدد قيمة منطقية تشير إلى ما إذا كان سيتم إغلاق كائن الاستجابة بعد حفظ المستند في الاستجابة. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | هذه السمة تقوم بتفعيل وظيفة استخراج الصورة أو النص لمستندات PDF مع طبقة OCR الفرعية. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | تنسيق حفظ البيانات. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | رد نداء لمعالجة أي تحذيرات تم إنشاؤها. يُرجع WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك يمكن للمستخدم أيضًا إرجاع Abort وفي هذه الحالة يجب أن تتوقف عملية الحفظ. |

## Fields

| Name | Description |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | معالجة الصفحات في عدة خيوط. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | أحيانًا تحتوي ملفات PDF على صور خلفية (للصفحات أو خلايا الجدول) تم إنشاؤها من عدة صور خلفية متطابقة موضوعة بالقرب من بعضها. في هذه الحالة، تقوم محركات التنسيق المستهدف (مثل MsWord لتنسيق DOCS) أحيانًا بإنشاء حدود مرئية بين أجزاء الصور الخلفية، لأن تقنياتهم في تنعيم حواف الصور (مضاد التعرج) تختلف عن Acrobat Reader. إذا بدا أن المستند المصدر يحتوي على مثل هذه الحدود المرئية بين أجزاء من نفس الصور الخلفية، يرجى محاولة استخدام هذا الإعداد للتخلص من هذا التأثير غير المرغوب فيه. انتبه! عادةً ما تؤدي هذه التحسينات في الجودة إلى إبطاء التحويل بشكل كبير، لذا، يرجى استخدام هذا الخيار فقط عندما يكون ذلك ضروريًا حقًا. |

### See Also

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)