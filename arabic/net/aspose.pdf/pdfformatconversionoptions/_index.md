---
title: PdfFormatConversionOptions
second_title: Aspose.PDF لمرجع .NET API
description: يمثل مجموعة من الخيارات لتحويل مستند PDF
type: docs
weight: 6030
url: /ar/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class

يمثل مجموعة من الخيارات لتحويل مستند PDF

```csharp
public class PdfFormatConversionOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor)(PdfFormat) | منشئ |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_1)(PdfFormat, ConvertErrorAction) | منشئ |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_3)(string, PdfFormat) | منشئ |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | منشئ |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_4)(string, PdfFormat, ConvertErrorAction) | منشئ |
| [PdfFormatConversionOptions](pdfformatconversionoptions#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | منشئ |

## الخصائص

| اسم | وصف |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default) { get; } | يحصل على كائن PdfFormatConversionOptions مع المعلمات الافتراضية |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext) { get; set; } | تتحكم هذه العلامة في محاذاة النص في المستند المحول. افتراضيًا ، لا يؤثر تحويل المستند على محاذاة النص ويترك النص كما هو. ولكن في بعض الحالات ، يتسبب استبدال الخط في تداخل النص أو مسافات إضافية في المستند المحول. عندما يتم تعيين هذه العلامة سيتم تنفيذ عمليات محاذاة خاصة. يجب تعيين هذه العلامة فقط لـ documents التي تواجه مشكلات مع النص المتداخل أو مسافات النص الإضافية التي تتسبب في استخدام هذا العلم في تقليل الأداء وفي بعض الحالات قد يؤدي إلى إتلاف محتوى النص. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction) { get; set; } | إجراء للصور ذات القناع الناعم . |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction) { get; set; } | الإجراء الخاص بالكائنات التي لا يمكن تحويلها |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy) { get; set; } | إستراتيجية (استراتيجيات) لاستبعاد الخطوط الزائدة وتقليل حجم ملف المستند. هذه المعلمة لها معنى فقط عند العلم[`OptimizeFileSize`](./optimizefilesize) تم تعيينه على "صحيح". بشكل افتراضي مجموعة من الاستراتيجياتSubsetFonts و RemoveDuplicatedFonts يستخدم . |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions) { get; } | خيارات للحالات التي يتعذر فيها تضمين بعض الخطوط في مستند PDF . |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format) { get; set; } | تنسيق PDF . |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename) { get; set; } | الحصول على أو تحديد اسم ملف ملف تعريف icc. في حالة وجود قيمة خالية ، يتم استخدام ملف تعريف icc الافتراضي. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode) { get; set; } | الحصول على / مجموعات تشغيل تدفقات الصور في الوضع غير المتزامن. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode) { get; set; } | تم تمكين وضع تحويل الذاكرة المنخفضة |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo) { get; set; } | الحصول على أو تحديد ما إذا كان سيتم تمرير البيانات من المعلومات إلى البيانات الأولية عند التحويل إلى PDF 2.0. صحيح افتراضيًا . |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename) { get; set; } | مسار الملف حيث سيتم تخزين التعليقات. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream) { get; set; } | دفق حيث سيتم تخزين التعليقات. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases) { get; } | يحمل الأعلام للتحكم في عملية تحويل PDF / A للحالات التي لا يتوافق فيها المستند المصدر مع مواصفات PDF / A . |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts) { get; } | هذه الخاصية خارج الملكية. يحتوي على جميع الخطوط (أسماء الخطوط) التي لم يتم العثور عليها على الكمبيوتر في تحويل PDF / A الأخير. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize) { get; set; } | الحصول على علامة أو تعيينها لتمكين / تعطيل وضع التحويل الخاص للحصول على مستند PDF / A بحجم ملف منخفض. لتشغيل التحسين لبنى بيانات أخرى ، مثل الرسم. يمكن أن تؤدي مجموعة هذه العلامة والوضع إلى تقليل حجم الملف بشكل كبير ولكن في نفس الوقت يمكن أن يؤدي إلى تقليل أداء التحويل بشكل ملحوظ . |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy) { get; set; } | إستراتيجية لمعالجة الرموز من منطقة الاستخدام الخاص لـ unicode (PUA) . |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy) { get; set; } | إستراتيجية لنسخ بيانات الترميز للخطوط الرمزية إذا كان خط TrueType الرمزي يحتوي على أكثر من جدول فرعي واحد للترميز. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction) { get; set; } | الإجراء الخاص بكائنات الصور المقنعة |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules) { get; set; } | قواعد حل المشكلات المتعلقة بتعيين الترميز الموحد. يمكن أن يكون فارغًا. |

## مجالات

| اسم | وصف |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy) | إستراتيجية لمحاذاة النص. هذه المعلمة لها معنى فقط عند العلم[`AlignText`](./aligntext) مضبوطة على true . |

### أنظر أيضا

* مساحة الاسم [Aspose.Pdf](../../aspose.pdf)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
