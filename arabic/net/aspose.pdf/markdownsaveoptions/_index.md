---
title: "فئة MarkdownSaveOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.MarkdownSaveOptions. تمثل فئة خيارات حفظ المستند بتنسيق markdown."
type: docs
weight: 7050
url: /ar/net/aspose.pdf/markdownsaveoptions/
---
## MarkdownSaveOptions class

يمثل فئة خيار حفظ المستند بتنسيق markdown.

```csharp
public class MarkdownSaveOptions : UnifiedSaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | احصل أو اضبط منطقة مستطيلة لاستخراج المحتوى إلى markdown. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا سيتم تخزين رموز الخط في الذاكرة المؤقتة أثناء إعداد صفحات aps. يحسن أداء تحويل PDF إلى صيغ أخرى لكنه يزيد من استهلاك الذاكرة. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا سيتم إغلاق كائن Response بعد حفظ المستند في الاستجابة. |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | احصل أو اضبط نمط التشديد للمستند المُنشأ. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | هذا السمة تفعّل وظيفة استخراج الصورة أو النص لمستندات PDF مع طبقة OCR الفرعية. |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | يحصل ويضبط خاصية تشير إلى ما إذا كان يجب استخراج الرسومات المتجهية. |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | يحدد مستويات العناوين المتوقعة لاستخدامها في استراتيجية التعرف على رؤوس الخطوط حسب حجم الخط FontSize. إذا تم تعيين قيمة هذه الخاصية، فسيتم اختيار استراتيجية التعرف على العناوين الخوارزمية عندما يتم تعيين !:PdfToMarkdown.HeadingRecognitionStrategy.Auto حتى إذا كان المستند يحتوي على إشارات مرجعية. |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | احصل أو اضبط استراتيجية التعرف على العناوين. |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | يحصل أو يضبط نمط العنوان للمستند المُولَّد. |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | يحصل أو يضبط نمط فاصل السطر للمستند المُولَّد. |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | يحصل ويضبط اسم الدليل لحفظ موارد المستند مثل الصور. إذا لم يتم تحديد القيمة، فستُكتب الصور في نفس الدليل الذي يوجد فيه ملف markdown نفسه. هذا ليس مسارًا، إنه مجرد اسم! سيتم إنشاء هذا الدليل تلقائيًا في الدليل الذي يحتوي على ملف markdown المحفوظ. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | تنسيق حفظ البيانات. |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | يحصل أو يضبط السماح بتحويل النص السفلي والعلوي. هذه القيمة صحيحة بشكل افتراضي. |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | يحصل ويضبط السماح باستخدام وسم img لإدراج الصور إلى يسار أو يمين النص. في هذه الحالة، في عارض markdown، سيلتف النص حول الصورة. |
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


