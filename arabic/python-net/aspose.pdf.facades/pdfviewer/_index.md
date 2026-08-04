---
title: "PdfViewer"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يمثل فئة لعرض أو طباعة ملف PDF."
type: docs
weight: 370
url: /ar/python-net/aspose.pdf.facades/pdfviewer/
---

## PdfViewer class

يمثل فئة لعرض أو طباعة ملف PDF.

يعرض نوع PdfViewer الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| PdfViewer() | ينشئ كائنًا جديدًا من [PdfViewer](/pdf/python-net/aspose.pdf.facades/pdfviewer/). |
| PdfViewer(document) | ينشئ نسخة جديدة من فئة PdfViewer |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| show_hidden_areas | يحصل أو يضبط العلامة التي تتحكم في إظهار المناطق المخفية على الصفحة. |
| print_status | يحصل على نتيجة مهمة الطباعة. إذا نجحت تكون null؛ وإلا كائن الاستثناء. |
| use_intermidiate_image | يحصل/يضبط استخدام تحويل صفحة PDF إلى ملف PNG وسيط أثناء الطباعة في وضع الملف. استخدمه عندما يكون حجم ملف الإخراج مهمًا. |
| coordinate_type | يحصل أو يضبط نوع إحداثيات الصفحة (صناديق Media/Crop). يتم استخدام قيمة CropBox كإعداد افتراضي. |
| print_as_image | يضبط أو يحصل على وضعية PdfViewer للطباعة كصورة. |
| page_count | يحصل على عدد صفحات ملف PDF الحالي. |
| password | يحصل أو يضبط كلمة مرور المستند المدخل. |
| print_page_dialog | يحصل أو يضبط قيمة منطقية تشير إلى ما إذا كان يتم إظهار حوار رقم الصفحة عند الطباعة. |
| print_as_grayscale | يحصل أو يضبط قيمة منطقية تشير إلى ما إذا كانت الصفحة تُطبع بالأبيض والأسود. القيمة الافتراضية هي false. |
| printer_job_name | يحصل أو يضبط اسم المستند في طابور الطباعة عند طباعة المستند. القيمة الافتراضية هي اسم الملف. |
| form_presentation_mode | يحصل أو يضبط وضع عرض النموذج. |
| rendering_options | يحصل أو يضبط خيارات العرض. |
| vertical_alignment | يحصل أو يضبط قيمة تشير إلى المحاذاة العمودية |
| horizontal_alignment | يحصل أو يضبط قيمة تشير إلى المحاذاة الأفقية |
| auto_resize | يحصل أو يضبط قيمة منطقية تشير إلى ما إذا كان سيتم طباعة الملف بحجم مُحسّن. |
| auto_rotate | يحصل أو يضبط قيمة منطقية تشير إلى ما إذا كان سيتم طباعة الملف بتدوير تلقائي |
| auto_rotate_mode | يحصل أو يضبط قيمة AutoRotateMode تشير إلى اتجاه التدوير |
| resolution | يحصل أو يضبط الدقة أثناء العرض والطباعة. كلما ارتفعت الدقة، كلما كان السرعة أبطأ. القيمة الافتراضية هي 150. |
| scale_factor | يحصل أو يضبط قيمة عددية عائمة تشير إلى معامل المقياس. القيمة الافتراضية هي 1.0. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| print_large_pdf(file_path) | يفتح ويطبع ملف Pdf كبير. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو حجمه <br/>             أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. |
| print_large_pdf(input_stream) | يفتح ويطبع تدفق Pdf كبير. إذا كان ملف Pdf الخاص بك يحتوي على مئات الصفحات أو أكثر أو حجمه <br/>             أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. |
| print_large_pdf(file_path, printer_settings) | يفتح ويطبع ملف Pdf كبير بإعدادات طابعة محددة. إذا كان ملف Pdf الخاص بك يحتوي على مئات <br/>             من الصفحات أو أكثر أو حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. |
| print_large_pdf(input_stream, printer_settings) | يفتح ويطبع تدفق Pdf كبير بإعدادات طابعة محددة. إذا كان ملف Pdf الخاص بك يحتوي على مئات <br/>             من الصفحات أو أكثر أو حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة للحصول على أداء أفضل. |
| print_large_pdf(file_path, page_settings, printer_settings) | يفتح ويطبع ملف Pdf كبير بإعدادات صفحة وإعدادات طابعة محددة. إذا كان ملف Pdf <br/>             يحتوي على مئات الصفحات أو أكثر أو حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة <br/>             للحصول على أداء أفضل. |
| print_large_pdf(input_stream, page_settings, printer_settings) | يفتح ويطبع تدفق PDF كبير مع إعدادات الصفحة المحددة وإعدادات الطابعة. إذا كان ملف PDF الخاص بك <br/> يحتوي على مئات الصفحات أو أكثر أو كان حجمه أكثر من 3 ميغابايت، يُنصح باستخدام هذه الطريقة <br/> للحصول على أداء أفضل. |
| print_document_with_settings(page_settings, printer_settings) | يطبع مستند PDF بالإعدادات. إذا لم يكن حجم المستند متوافقًا مع حجم الصفحة، سيقوم pdf.kit بتمديده ليتناسب مع حجم الصفحة. |
| print_document_with_settings(printer_settings) | يطبع مستند PDF بالإعدادات. إذا لم يكن حجم المستند متوافقًا مع حجم الصفحة، سيقوم pdf.kit بتمديده ليتناسب مع حجم الصفحة. |
| open_pdf_file(file_path) | يفتح ملف PDF، لكنه لا يقوم فعليًا بفك تشفير صفحات ملف PDF. |
| open_pdf_file(input_stream) | يفتح تدفق ملف PDF. لكنه لا يقوم فعليًا بفك تشفير صفحات ملف PDF. |
| bind_pdf(src_file) | يُهيئ الـ facade. |
| bind_pdf(src_stream) | يُهيئ الـ facade. |
| bind_pdf(src_doc) | يُهيئ الـ facade. |
| save(dest_file) | يحفظ مستند PDF الناتج إلى ملف. |
| save(dest_stream) | يحفظ مستند PDF الناتج إلى تدفق. |
| decode_all_pages() | احصل على صفحات ملف PDF الحالي. |
| decode_page(page_number) | يفك تشفير صفحة من ملف PDF واحد. |
| print_document_with_setup() | يطبع مستند PDF باستخدام حوار الإعداد. اختر طابعة باستخدام الحوار. |
| print_document() | يطبع مستند PDF باستخدام حوار الإعداد. اختر طابعة باستخدام الحوار. |
| get_default_page_settings() | يحصل على إعدادات الصفحة الافتراضية. |
| get_default_printer_settings() | يحصل على إعدادات الطابعة الافتراضية. |
| close_pdf_file() | يغلق ملف PDF الحالي. |
| close() | يغلق ملف PDF الحالي. |

### انظر أيضًا

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

