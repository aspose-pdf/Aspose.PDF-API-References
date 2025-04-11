---
title: Class PdfFormatConversionOptions
second_title: Aspose.PDF for .NET API Reference
description: تمثل فئة Aspose.Pdf.PdfFormatConversionOptions مجموعة من الخيارات لتحويل مستند PDF
type: docs
weight: 8380
url: /ar/net/aspose.pdf/pdfformatconversionoptions/
---
## فئة PdfFormatConversionOptions

تمثل مجموعة من الخيارات لتحويل مستند PDF

```csharp
public class PdfFormatConversionOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor)(PdfFormat) | منشئ |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_1)(PdfFormat, ConvertErrorAction) | منشئ |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_3)(string, PdfFormat) | منشئ |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | منشئ |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_4)(string, PdfFormat, ConvertErrorAction) | منشئ |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | منشئ |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default/) { get; } | يحصل على كائن PdfFormatConversionOptions مع معلمات افتراضية |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | يتحكم هذا العلم في محاذاة النص في المستند المحول. بشكل افتراضي، لا تؤثر تحويلات المستند على محاذاة النص وتترك النص كما هو. ولكن في بعض الحالات، يتسبب استبدال الخط في تداخل النص أو وجود مسافات إضافية في المستند المحول. عندما يتم تعيين هذا العلم، سيتم تنفيذ عمليات محاذاة خاصة. يجب تعيين هذا العلم فقط للمستندات التي تعاني من مشاكل مع النص المتداخل أو المسافات الإضافية، لأن استخدام هذا العلم يقلل من الأداء وفي بعض الحالات قد يتسبب في تلف محتوى النص. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | إجراء للصور ذات القناع الناعم. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | إجراء للكائنات التي لا يمكن تحويلها |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | استراتيجية(ات) لاستبعاد الخطوط الزائدة وتقليل حجم ملف المستند. هذه المعلمة لها معنى فقط عندما يتم تعيين العلم [`OptimizeFileSize`](./optimizefilesize/) إلى true. بشكل افتراضي، يتم استخدام مجموعة من الاستراتيجيات SubsetFonts و RemoveDuplicatedFonts. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | خيارات للحالات التي لا يمكن فيها تضمين بعض الخطوط في مستند PDF. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | تنسيق PDF. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | يحصل على أو يحدد اسم ملف ملف تعريف icc. في حالة null، يتم استخدام ملف تعريف icc الافتراضي. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | يحصل/يحدد تشغيل تدفقات الصور في وضع غير متزامن. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | هل تم تمكين وضع تحويل الذاكرة المنخفضة |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | يحصل على أو يحدد ما إذا كان يجب تمرير البيانات من Info إلى Metadata عند التحويل إلى PDF 2.0. صحيح بشكل افتراضي. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | المسار إلى الملف الذي سيتم تخزين التعليقات فيه. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | التدفق الذي سيتم تخزين التعليقات فيه. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | يحمل الأعلام للتحكم في عملية تحويل PDF/A للحالات التي لا يتوافق فيها المستند المصدر مع مواصفات PDF/A. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | هذه الخاصية هي خاصية خارجية. تحمل جميع الخطوط (أسماء الخطوط) التي لم يتم العثور عليها على الكمبيوتر في آخر تحويل PDF/A. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | يحصل على أو يحدد علمًا يمكّن/يعطل وضع التحويل الخاص للحصول على مستند PDF/A بحجم ملف مخفض. الآن يؤثر هذا العلم على تحسين الخطوط المستخدمة في مستند PDF، ومن المحتمل في المستقبل، سيتم استخدام هذا العلم أيضًا لتشغيل تحسينات لهياكل بيانات أخرى، مثل الرسوم البيانية. يمكن أن يؤدي تعيين هذا العلم والوضع إلى تقليل حجم الملف بشكل كبير، ولكن في نفس الوقت قد يقلل بشكل كبير من أداء التحويل. |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | يحصل على أو يحدد [`OutputIntent`](../outputintent/) لتحويل تنسيق PDF. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | استراتيجية لمعالجة الرموز من منطقة الاستخدام الخاص (PUA) في يونيكود. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | استراتيجية لنسخ بيانات الترميز للخطوط الرمزية إذا كان الخط الرمزي TrueType يحتوي على أكثر من جدول ترميز واحد. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | إجراء لكائنات الصور المmasked |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | قواعد لحل المشكلات المتعلقة بتخطيط يونيكود. يمكن أن تكون null. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | استراتيجية لمحاذاة النص. هذه المعلمة لها معنى فقط عندما يتم تعيين العلم [`AlignText`](./aligntext/) إلى true. |

### انظر أيضًا

* مساحة الأسماء [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)