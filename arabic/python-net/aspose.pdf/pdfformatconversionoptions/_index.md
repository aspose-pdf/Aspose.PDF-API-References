---
title: "PdfFormatConversionOptions"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يمثل مجموعة من الخيارات لتحويل مستند PDF"
type: docs
weight: 1220
url: /ar/python-net/aspose.pdf/pdfformatconversionoptions/
---

## PdfFormatConversionOptions class

يمثل مجموعة من الخيارات لتحويل مستند PDF

يعرض نوع PdfFormatConversionOptions الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| PdfFormatConversionOptions(output_log_file_name, format, action) | ينشئ مثيلًا جديدًا من فئة PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_file_name, format) | ينشئ مثيلًا جديدًا من فئة PdfFormatConversionOptions |
| PdfFormatConversionOptions(format) | ينشئ مثيلًا جديدًا من فئة PdfFormatConversionOptions |
| PdfFormatConversionOptions(format, action) | ينشئ مثيلًا جديدًا من فئة PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_file_name, format, action, transparency_action) | ينشئ مثيلًا جديدًا من فئة PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_stream, format, action) | ينشئ مثيلًا جديدًا من فئة PdfFormatConversionOptions |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| is_async_image_streams_conversion_mode | يحصل/يضبط تشغيل تدفقات الصور في وضع غير متزامن. |
| is_low_memory_mode | هل تم تمكين وضع التحويل منخفض الذاكرة |
| format | تنسيق PDF. |
| log_file_name | المسار إلى الملف حيث سيتم تخزين التعليقات. |
| log_stream | المجرى حيث سيتم تخزين التعليقات. |
| error_action | الإجراء للأشياء التي لا يمكن تحويلها |
| transparency_action | الإجراء للأشياء ذات القناع الصوري |
| convert_soft_mask_action | الإجراء للصور ذات القناع الناعم. |
| default | يحصل على كائن PdfFormatConversionOptions مع المعلمات الافتراضية |
| non_specification_cases | يحمل علامات للتحكم في عملية تحويل PDF/A للحالات التي لا يتطابق فيها المستند المصدر<br/>            مع مواصفات PDF/A. |
| symbolic_font_encoding_strategy | استراتيجية لنسخ بيانات الترميز للخطوط الرمزية إذا كان الخط TrueType الرمزي<br/>            يحتوي على أكثر من جدول ترميز فرعي. |
| align_text | هذه العلامة تتحكم في محاذاة النص في المستند المحوَّل. بشكل افتراضي لا تؤثر عملية تحويل المستند <br/>            على محاذاة النص وتترك النص كما هو. ولكن في بعض الحالات قد يتسبب استبدال الخط<br/>            في تداخل النص أو وجود مسافات إضافية في المستند المحوَّل. عندما يتم تعيين هذه العلامة<br/>            سيتم تنفيذ عمليات محاذاة خاصة. يجب تعيين هذه العلامة فقط للمستندات<br/>            التي تعاني من مشاكل تداخل النص أو مسافات نصية إضافية لأن استخدام هذه العلامة يقلل<br/>            من الأداء وقد يؤدي في بعض الحالات إلى إفساد محتوى النص. |
| pua_text_processing_strategy | استراتيجية لمعالجة الرموز من منطقة الاستخدام الخاص في Unicode (PUA). |
| optimize_file_size | يحصل أو يضبط علامة تمكّن/تعطل وضع التحويل الخاص للحصول على مستند PDF/A بحجم ملف أصغر.<br/>            الآن تؤثر هذه العلامة على تحسين الخطوط المستخدمة في مستند PDF، وربما في المستقبل، ستُستخدم هذه العلامة <br/>            أيضًا لتفعيل تحسين هياكل بيانات أخرى، مثل الرسوميات.  <br/>            مجموعة هذه العلامة والوضع يمكن أن تقلل حجم الملف بشكل كبير ولكن في الوقت نفسه قد<br/>            تقلل أداء التحويل بشكل ملحوظ. |
| exclude_fonts_strategy | استراتيجية (استراتيجيات) لاستبعاد الخطوط الزائدة وتقليل حجم ملف المستند. <br/>            هذا المعامل له معنى فقط عندما تكون العلامة [optimize_file_size](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) مضبوطة على true.<br/>            بشكل افتراضي يتم استخدام مجموعة من الاستراتيجيات [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) و<br/>            [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/). |
| font_embedding_options | خيارات للحالات التي لا يمكن فيها تضمين بعض الخطوط في مستند PDF. |
| unicode_processing_rules | قواعد لحل المشكلات المتعلقة بترميز Unicode. يمكن أن تكون فارغة. |
| icc_profile_file_name | يحصل أو يضبط اسم ملف ملف تعريف ICC. في حالة كونها null يُستخدم ملف تعريف ICC الافتراضي. |
| not_accessible_fonts | هذه الخاصية هي خاصية خارجية. تحتفظ بجميع الخطوط (أسماء الخطوط) التي لم يتم العثور عليها على الحاسوب <br/>            في آخر تحويل PDF/A. |
| is_transfer_info | يحصل أو يضبط ما إذا كان يجب نقل البيانات من Info إلى Metadata عند التحويل إلى PDF 2.0. القيمة الافتراضية true. |
| align_strategy | استراتيجية لمحاذاة النص. هذا المعامل له معنى فقط عندما تكون العلامة [align_text](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) مضبوطة على true. |

### انظر أيضًا

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

