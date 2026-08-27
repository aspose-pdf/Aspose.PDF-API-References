---
title: "PdfFileStamp"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "فئة لإضافة طوابع (علامة مائية أو خلفية) إلى ملفات PDF."
type: docs
weight: 320
url: /ar/python-net/aspose.pdf.facades/pdffilestamp/
---

## PdfFileStamp class

فئة لإضافة طوابع (علامة مائية أو خلفية) إلى ملفات PDF.

يعرض نوع PdfFileStamp الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| PdfFileStamp(input_file, output_file) | ينشئ مثيلاً جديداً من فئة PdfFileStamp |
| PdfFileStamp(input_stream, output_stream) | ينشئ مثيلاً جديداً من فئة PdfFileStamp |
| PdfFileStamp(input_file, output_file, keep_security) | ينشئ مثيلاً جديداً من فئة PdfFileStamp |
| PdfFileStamp(input_stream, output_stream, keep_security) | ينشئ مثيلاً جديداً من فئة PdfFileStamp |
| PdfFileStamp() | منشئ PdfFileStamp.<br/>            يمكن تحديد ملف الإدخال وملف الإخراج عبر الخصائص المقابلة. |
| PdfFileStamp(document) | ينشئ مثيلاً جديداً من فئة PdfFileStamp |
| PdfFileStamp(document, output_file) | ينشئ مثيلاً جديداً من فئة PdfFileStamp |
| PdfFileStamp(document, output_stream) | ينشئ مثيلاً جديداً من فئة PdfFileStamp |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| مستند | يحصل على واجهة المستند التي يعمل عليها. |
| optimize_size | يحصل أو يضبط علامة التحسين. يتم دمج تدفقات الموارد المتساوية في الملف الناتج في كائن PDF واحد إذا تم تعيين هذه العلامة. <br/>            يتيح ذلك تقليل حجم الملف الناتج لكنه قد يسبب تنفيذًا أبطأ ومتطلبات ذاكرة أكبر.<br/>            القيمة الافتراضية: false. |
| keep_security | يحافظ على الأمان إذا كان true. (سيتم تنفيذ هذه الميزة في الإصدارات القادمة). |
| input_file | يحصل أو يضبط الاسم والمسار لملف الإدخال. |
| input_stream | يحصل أو يضبط تدفق الإدخال. |
| output_file | يحصل أو يضبط الاسم والمسار لملف الإخراج. |
| output_stream | يحصل أو يضبط تدفق الإخراج. |
| page_number_rotation | يحصل أو يضبط دوران رقم الصفحة. الدوران بالدرجات. القيمة الافتراضية هي 0. |
| page_height | يحصل على ارتفاع الصفحة الأولى في ملف المصدر. |
| page_width | يحصل على عرض الصفحة الأولى في ملف الإدخال. |
| starting_number | يحصل أو يضبط الرقم الابتدائي للصفحة الأولى في ملف الإدخال. سيتم ترقيم الصفحات التالية بدءًا من هذه القيمة. <br/>            على سبيل المثال إذا تم تعيين StartingNumber إلى 100، ستحصل صفحات المستند على الأرقام 100، 101، 102... |
| numbering_style | يحصل أو يضبط نمط ترقيم الصفحات. القيم الممكنة: NumeralsArabic، NumeralsRomanUppercase، NumeralsRomanLowercase، LettersAppercase، LettersLowercase |
| stamp_id | معرّف Stamp ID للطابع التالي المضاف (بما في ذلك رؤوس/تذييلات الصفحات/أرقام الصفحات). |
| POS_BOTTOM_MIDDLE | موضع أسفل الوسط. |
| POS_BOTTOM_RIGHT | موضع أسفل اليمين. |
| POS_UPPER_RIGHT | موضع أعلى اليمين. |
| POS_SIDES_RIGHT | موضع اليمين. |
| POS_UPPER_MIDDLE | موضع أعلى الوسط. |
| POS_BOTTOM_LEFT | موضع أسفل اليسار. |
| POS_SIDES_LEFT | موضع اليسار. |
| POS_UPPER_LEFT | موضع أعلى اليسار. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| bind_pdf(src_file) | يربط مستند PDF للتحرير. |
| bind_pdf(src_stream) | يربط مستند PDF للتحرير. |
| bind_pdf(src_doc) | يربط مستند PDF للتحرير. |
| save(dest_file) | يحفظ النتيجة في الملف المحدد. |
| save(dest_stream) | يحفظ المستند في الدفق المحدد. |
| add_page_number(format_string) | إضافة رقم الصفحة إلى الملف. قد يحتوي نص رقم الصفحة على علامة # التي سيتم استبدالها برقم الصفحة. <br/>            يتم وضع رقم الصفحة في أسفل الصفحة مركّزًا أفقيًا. |
| add_page_number(formatted_text) | يضيف رقم الصفحة إلى الصفحة. قد يحتوي رقم الصفحة على علامة # التي سيتم استبدالها برقم الصفحة.<br/>            يتم وضع رقم الصفحة في أسفل الصفحة مركّزًا أفقيًا. |
| add_page_number(format_string, position, left_margin, right_margin, top_margin, bottom_margin) | يضيف رقم الصفحة إلى صفحات المستند. |
| add_page_number(format_string, x, y) | يضيف رقم الصفحة إلى صفحات المستند. |
| add_page_number(formatted_text, position, left_margin, right_margin, top_margin, bottom_margin) | يضيف رقم الصفحة إلى صفحات المستند. |
| add_page_number(formatted_text, x, y) | يضيف رقم الصفحة إلى صفحات المستند. |
| add_page_number(format_string, position) | يضيف رقم الصفحة إلى صفحات المستند. |
| add_page_number(formatted_text, position) | يضيف رقم الصفحة إلى صفحات المستند. |
| add_header(formatted_text, top_margin) | يضيف رأسًا إلى الصفحة. |
| add_header(formatted_text, top_margin, left_margin, right_margin) | يضيف رأسًا إلى الصفحة. |
| add_header(image_file, top_margin) | يضيف الصورة كرأس للصفحات في الملف. |
| add_header(image_file, top_margin, left_margin, right_margin) | يضيف الصورة كرأس للصفحات في الملف. |
| add_header(image_stream, top_margin) | يضيف الصورة كرأس على الصفحات. |
| add_header(input_stream, top_margin, left_margin, right_margin) | يضيف الصورة كرأس على الصفحات. |
| add_footer(formatted_text, bottom_margin) | يضيف تذييلًا إلى صفحات المستند. |
| add_footer(formatted_text, bottom_margin, left_margin, right_margin) | يضيف تذييلًا إلى صفحات المستند. |
| add_footer(image_file, bottom_margin) | يضيف الصورة كتذييل للصفحات في المستند. |
| add_footer(image_file, bottom_margin, left_margin, right_margin) | يضيف الصورة كتذييل للصفحات في المستند. |
| add_footer(image_stream, bottom_margin) | يضيف الصورة كتذييل للصفحة. |
| add_footer(image_stream, bottom_margin, left_margin, right_margin) | يضيف الصورة كتذييل للصفحة. |
| close() | يغلق الملفات المفتوحة ويحفظ التغييرات. <br/>            تحذير. إذا تم تحديد تدفقات الإدخال أو الإخراج فإنها لا تُغلق بواسطة طريقة Close(). |
| add_stamp(stamp) | يضيف ختمًا إلى الملف. |

### انظر أيضًا

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

