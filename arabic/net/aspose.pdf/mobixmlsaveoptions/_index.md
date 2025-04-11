---
title: Class MobiXmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.MobiXmlSaveOptions. خيارات الحفظ للتصدير إلى تنسيق Xml
type: docs
weight: 6980
url: /ar/net/aspose.pdf/mobixmlsaveoptions/
---
## فئة MobiXmlSaveOptions

خيارات الحفظ للتصدير إلى تنسيق Xml

```csharp
public class MobiXmlSaveOptions : UnifiedSaveOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MobiXmlSaveOptions](mobixmlsaveoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | يحصل أو يحدد قيمة منطقية تشير إلى ما إذا كان سيتم تخزين رموز الخطوط أثناء إعداد صفحات aps. يحسن أداء تحويل PDF إلى تنسيقات أخرى ولكنه يزيد من استهلاك الذاكرة. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | يحصل أو يحدد قيمة منطقية تشير إلى ما إذا كان سيتم إغلاق كائن الاستجابة بعد حفظ المستند في الاستجابة. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | هذه السمة تفعيل الوظيفة لاستخراج الصورة أو النص لمستندات PDF مع طبقة OCR فرعية. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | تنسيق حفظ البيانات. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | رد الاتصال لمعالجة أي تحذيرات تم إنشاؤها. يعيد WarningHandler عنصر تعداد ReturnAction يحدد إما Continue أو Abort. Continue هو الإجراء الافتراضي وتستمر عملية الحفظ، ومع ذلك يمكن للمستخدم أيضًا إرجاع Abort وفي هذه الحالة يجب أن تتوقف عملية الحفظ. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | معالجة الصفحات في عدة خيوط. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | أحيانًا تحتوي ملفات PDF على صور خلفية (للصفحات أو خلايا الجدول) تم إنشاؤها من عدة صور خلفية متكررة متطابقة موضوعة بجانب بعضها البعض. في هذه الحالة، تقوم محركات التنسيق المستهدف (مثل MsWord لتنسيق DOCS) أحيانًا بإنشاء حدود مرئية بين أجزاء الصور الخلفية، لأن تقنياتهم في تنعيم حواف الصور (مضاد التعرج) تختلف عن Acrobat Reader. إذا بدا أن المستند المصدر يحتوي على مثل هذه الحدود المرئية بين أجزاء من نفس الصور الخلفية، يرجى محاولة استخدام هذا الإعداد للتخلص من هذا التأثير غير المرغوب فيه. انتباه! عادةً ما تؤدي هذه التحسينات في الجودة إلى إبطاء التحويل بشكل كبير، لذا، يرجى استخدام هذا الخيار فقط عندما يكون ذلك ضروريًا حقًا. |

### انظر أيضًا

* فئة [UnifiedSaveOptions](../unifiedsaveoptions/)
* مساحة الأسماء [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)