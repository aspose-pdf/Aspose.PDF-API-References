---
title: "الفئة PdfAConvertOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Plugins.PdfAConvertOptions. تمثل الخيارات لتحويل مستندات PDF إلى تنسيق PDF/A باستخدام المكوّن PdfAConverter"
type: docs
weight: 9140
url: /ar/net/aspose.pdf.plugins/pdfaconvertoptions/
---
## PdfAConvertOptions class

تمثل الخيارات لتحويل مستندات PDF إلى تنسيق PDF/A باستخدام المكوّن [`PdfAConverter`](../pdfaconverter/).

```csharp
public sealed class PdfAConvertOptions : PdfAOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfAConvertOptions](pdfaconvertoptions/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هناك حاجة إلى وسائل إضافية للحفاظ على محاذاة النص أثناء عملية تحويل PDF/A. |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | يحصل أو يعيّن الإجراء المتخذ للكائنات التي لا يمكن تحويلها. |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | يحصل أو يعيّن الاستراتيجية لإزالة الخطوط لتقليل حجم ملف الإخراج أثناء عملية تحويل PDF/A. |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | يحصل على الخيارات لمعالجة الخطوط التي لا يمكن تضمينها في المستند. |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | يحصل أو يعيّن اسم ملف تعريف ICC (International Color Consortium) الذي سيُستخدم في تحويل PDF/A بدلاً من الملف الافتراضي. |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | يحصل على مجموعة مصادر البيانات |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان وضع الذاكرة المنخفضة مفعلاً أثناء عملية تحويل PDF/A. |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | يحصل أو يعيّن مصدر البيانات لإخراج السجل. |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | يحصل على العلامات التي تتحكم في تحويل PDF/A للحالات التي لا يتطابق فيها مستند PDF المصدر مع مواصفة PDF. |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب محاولة تقليل حجم الملف أثناء عملية تحويل PDF/A. |
| [Outputs](../../aspose.pdf.plugins/pdfaconvertoptions/outputs/) { get; } | يحصل على مجموعة الأهداف المضافة (مصادر بيانات ملف أو تدفق) لحفظ نتائج العملية. |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | يحصل أو يعيّن نسخة معيار PDF/A التي ستُستخدم للتحقق أو التحويل. |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | يحصل أو يعيّن الاستراتيجية لمعالجة رموز منطقة الاستخدام الخاص (PUA) في مستند PDF. |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | يحصل أو يعيّن الإجراء الذي سيُتخذ أثناء تحويل الصور ذات الأقنعة الناعمة. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | يحصل أو يعيّن الاستراتيجية لترميز الخطوط الرمزية عند التحويل إلى تنسيق PDF/A. |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | يحصل أو يعيّن القواعد لمعالجة جداول ToUnicode CMap وعدم ربطها برموز Unicode أثناء عملية تحويل PDF/A. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | يضيف مصدر بيانات جديد إلى المجموعة |
| [AddOutput](../../aspose.pdf.plugins/pdfaconvertoptions/addoutput/)(IDataSource) | يضيف هدف حفظ نتيجة جديد. |

### انظر أيضًا

* class [PdfAOptionsBase](../pdfaoptionsbase/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


