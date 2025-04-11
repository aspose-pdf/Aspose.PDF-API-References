---
title: Class MarkdownSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.MarkdownSaveOptions. تمثل فئة خيارات حفظ المستند في تنسيق Markdown
type: docs
weight: 6910
url: /ar/net/aspose.pdf/markdownsaveoptions/
---
## فئة MarkdownSaveOptions

تمثل فئة خيارات حفظ المستند في تنسيق Markdown.

```csharp
public class MarkdownSaveOptions : UnifiedSaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | الحصول على أو تعيين منطقة مستطيلة لاستخراج المحتوى إلى Markdown. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | يحصل أو يحدد قيمة منطقية تشير إلى ما إذا كانت رموز الخطوط ستُخزن أثناء إعداد صفحات APS. يحسن أداء تحويل PDF إلى تنسيقات أخرى ولكنه يزيد من استهلاك الذاكرة. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | يحصل أو يحدد قيمة منطقية تشير إلى ما إذا كان سيتم إغلاق كائن الاستجابة بعد حفظ المستند في الاستجابة. |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | يحصل أو يحدد نمط التأكيد للمستند الناتج. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | هذه السمة تفعيل وظيفة استخراج الصورة أو النص لمستندات PDF مع طبقة OCR. |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | يحصل ويحدد خاصية تشير إلى ما إذا كان يجب استخراج الرسومات المتجهة. |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | يحدد مستويات العناوين المتوقعة لاستخدامها في استراتيجية التعرف على العناوين بحجم الخط. إذا تم تعيين قيمة هذه الخاصية، فسيتم اختيار استراتيجية التعرف على العناوين !:PdfToMarkdown.HeadingRecognitionStrategy.Heuristic عند تعيين استراتيجيات !:PdfToMarkdown.HeadingRecognitionStrategy.Auto حتى لو كان المستند يحتوي على إشارات مرجعية. |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | يحصل أو يحدد استراتيجية التعرف على العناوين. |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | يحصل أو يحدد نمط العنوان للمستند الناتج. |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | يحصل أو يحدد نمط فواصل الأسطر للمستند الناتج. |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | يحصل ويحدد اسم الدليل لحفظ موارد المستند مثل الصور. إذا لم يتم تحديد القيمة، فسيتم كتابة الصور إلى نفس الدليل مثل ملف Markdown نفسه. هذا ليس مسارًا، إنه مجرد اسم! سيتم إنشاء هذا الدليل تلقائيًا في الدليل الذي يحتوي على ملف Markdown المحفوظ. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | تنسيق حفظ البيانات. |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | يحصل ويحدد السماح بتحويل النص السفلي والنص العلوي. هذه القيمة صحيحة بشكل افتراضي. |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | يحصل ويحدد السماح باستخدام علامة img لإدراج الصور إلى يسار ويمين النص. في هذه الحالة، في عارض Markdown، سيتحول النص حول الصورة. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | رد الاتصال لمعالجة أي تحذيرات تم إنشاؤها. يعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك يمكن للمستخدم أيضًا إرجاع Abort وفي هذه الحالة يجب أن تتوقف عملية الحفظ. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | معالجة الصفحات في عدة خيوط. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | أحيانًا تحتوي ملفات PDF على صور خلفية (للصفحات أو خلايا الجدول) تم إنشاؤها من عدة صور خلفية متطابقة موضوعة بجوار بعضها البعض. في هذه الحالة، تقوم محركات تنسيق الهدف (مثل MsWord لتنسيق DOCS) أحيانًا بإنشاء حدود مرئية بين أجزاء الصور الخلفية، لأن تقنياتهم في تنعيم حواف الصور (مضاد التعرج) تختلف عن Acrobat Reader. إذا بدا أن المستند المصدر يحتوي على مثل هذه الحدود المرئية بين أجزاء من نفس الصور الخلفية، يرجى محاولة استخدام هذا الإعداد للتخلص من هذا التأثير غير المرغوب فيه. انتبه! عادةً ما تؤدي هذه التحسينات في الجودة إلى إبطاء التحويل بشكل كبير، لذا، يرجى استخدام هذا الخيار فقط عندما يكون ذلك ضروريًا حقًا. |

### انظر أيضًا

* فئة [UnifiedSaveOptions](../unifiedsaveoptions/)
* مساحة الأسماء [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)