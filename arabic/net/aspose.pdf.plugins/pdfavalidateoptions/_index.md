---
title: Class PdfAValidateOptions
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Plugins.PdfAValidateOptions. تمثل الخيارات للتحقق من توافق PDF/A لوثائق PDF باستخدام مكون PdfAConverter
type: docs
weight: 9030
url: /ar/net/aspose.pdf.plugins/pdfavalidateoptions/
---
## فئة PdfAValidateOptions

تمثل الخيارات للتحقق من توافق PDF/A لوثائق PDF باستخدام مكون [`PdfAConverter`](../pdfaconverter/) .

```csharp
public sealed class PdfAValidateOptions : PdfAOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfAValidateOptions](pdfavalidateoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | يحصل أو يحدد قيمة تشير إلى ما إذا كانت وسائل إضافية ضرورية للحفاظ على محاذاة النص أثناء عملية تحويل PDF/A. |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | يحصل أو يحدد الإجراء الذي يجب اتخاذه بالنسبة للأشياء التي لا يمكن تحويلها. |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | يحصل أو يحدد الاستراتيجية لإزالة الخطوط لتقليل حجم الملف الناتج أثناء عملية تحويل PDF/A. |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | يحصل على الخيارات لمعالجة الخطوط التي لا يمكن تضمينها في الوثيقة. |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | يحصل أو يحدد اسم ملف ملف تعريف ICC (التحالف الدولي للألوان) الذي سيتم استخدامه لتحويل PDF/A بدلاً من الافتراضي. |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | يحصل على مجموعة من مصادر البيانات |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | يحصل أو يحدد قيمة تشير إلى ما إذا كان وضع الذاكرة المنخفضة مفعلًا أثناء عملية تحويل PDF/A. |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | يحصل أو يحدد مصدر البيانات لخرج السجل. |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | يحصل على العلامات التي تتحكم في تحويل PDF/A للحالات التي لا يتوافق فيها مستند PDF المصدر مع مواصفات PDF. |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | يحصل أو يحدد قيمة تشير إلى ما إذا كان يجب محاولة تقليل حجم الملف أثناء عملية تحويل PDF/A. |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | يحصل أو يحدد إصدار معيار PDF/A الذي سيتم استخدامه للتحقق أو التحويل. |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | يحصل أو يحدد الاستراتيجية لمعالجة رموز منطقة الاستخدام الخاص (PUA) في مستند PDF. |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | يحصل أو يحدد الإجراء الذي يجب اتخاذه أثناء تحويل الصور ذات الأقنعة الناعمة. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | يحصل أو يحدد الاستراتيجية لترميز الخطوط الرمزية عند التحويل إلى تنسيق PDF/A. |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | يحصل أو يحدد القواعد لمعالجة جداول CMap ToUnicode وغير المرتبطة برموز Unicode أثناء عملية تحويل PDF/A. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | يضيف مصدر بيانات جديد إلى المجموعة |

### انظر أيضًا

* فئة [PdfAOptionsBase](../pdfaoptionsbase/)
* مساحة الأسماء [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* التجميع [Aspose.PDF](../../)