---
title: "الفئة PdfFormatConversionOptions"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.PdfFormatConversionOptions. تمثل مجموعة من الخيارات لتحويل مستند PDF"
type: docs
weight: 8520
url: /ar/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class

يمثل مجموعة من الخيارات لتحويل مستند PDF

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
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default/) { get; } | يحصل على كائن PdfFormatConversionOptions مع المعلمات الافتراضية |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | تتحكم هذه العلامة في محاذاة النص في المستند المحول. بشكل افتراضي لا تؤثر عملية تحويل المستند على محاذاة النص وتترك النص كما هو. لكن في بعض الحالات قد يتسبب استبدال الخطوط في تداخل النص أو وجود مسافات إضافية في المستند المحول. عندما يتم تعيين هذه العلامة، سيتم تنفيذ عمليات محاذاة خاصة. يجب تعيين هذه العلامة فقط للمستندات التي تواجه مشاكل في تداخل النص أو مسافات نصية إضافية، لأن استخدام هذه العلامة يقلل من الأداء وقد يفسد محتوى النص في بعض الحالات. |
| [AutoTaggingSettings](../../aspose.pdf/pdfformatconversionoptions/autotaggingsettings/) { get; set; } | يحصل أو يضبط الإعدادات للوسم التلقائي أثناء تحويل صيغة PDF. |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | الإجراء للصور ذات القناع الناعم. |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | الإجراء للكائنات التي لا يمكن تحويلها |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | استراتيجية (استراتيجيات) لاستبعاد الخطوط الزائدة وتقليل حجم ملف المستند. لا يكون لهذا المعامل معنى إلا عندما تكون العلامة [`OptimizeFileSize`](./optimizefilesize/) مضبوطة على true. بشكل افتراضي يتم استخدام مجموعة من الاستراتيجيات SubsetFonts و RemoveDuplicatedFonts. |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | خيارات للحالات التي لا يمكن فيها تضمين بعض الخطوط في مستند PDF. |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | صيغة PDF. |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | يحصل أو يضبط اسم ملف ملف تعريف icc. في حالة كون القيمة null يتم استخدام ملف تعريف icc الافتراضي. |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | يحصل/يضبط تشغيل تدفقات الصور في الوضع غير المتزامن. |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | هل تم تمكين وضع التحويل منخفض الذاكرة |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | يحصل أو يضبط ما إذا كان سيتم نقل البيانات من Info إلى Metadata عند التحويل إلى PDF 2.0. القيمة الافتراضية true. |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | المسار إلى الملف حيث سيتم تخزين التعليقات. |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | الدفق حيث سيتم تخزين التعليقات. |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | يحمل العلامات للتحكم في عملية تحويل PDF/A للحالات التي لا يتوافق فيها المستند المصدر مع مواصفات PDF/A. |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | هذه الخاصية هي خاصية خروج. إنها تحمل جميع الخطوط (أسماء الخطوط) التي لم يتم العثور عليها على الحاسوب في آخر تحويل PDF/A. |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | يحصل أو يضبط علامة تمكّن/تعطل وضع التحويل الخاص للحصول على مستند PDF/A بحجم ملف أصغر. الآن تؤثر هذه العلامة على تحسين الخطوط المستخدمة في مستند PDF، وربما في المستقبل ستُستخدم هذه العلامة لتفعيل تحسين هياكل بيانات أخرى، مثل الرسومات. مجموعة هذه العلامة والوضع يمكن أن تقلل بشكل كبير من حجم الملف ولكن في الوقت نفسه قد تقلل بشكل كبير من أداء التحويل. |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | يحصل أو يضبط الـ [`OutputIntent`](../outputintent/) لتحويل صيغة PDF. |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | استراتيجية لمعالجة الرموز من منطقة الاستخدام الخاص في Unicode (PUA). |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | استراتيجية لنسخ بيانات الترميز للخطوط الرمزية إذا كان الخط TrueType الرمزي يحتوي على أكثر من جدول ترميز فرعي. |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | إجراء للكائنات ذات القناع الصوري |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | قواعد لحل المشكلات المتعلقة بخرائط Unicode. يمكن أن تكون فارغة. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | استراتيجية لمحاذاة النص. لا يكون لهذا المعامل معنى إلا عندما يتم تعيين العلامة [`AlignText`](./aligntext/) إلى true. |

### انظر أيضًا

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


