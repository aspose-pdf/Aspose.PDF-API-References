---
title: "PdfFileMend"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يمثل فئة لإضافة النصوص والصور على صفحات مستند PDF الموجود."
type: docs
weight: 280
url: /ar/python-net/aspose.pdf.facades/pdffilemend/
---

## PdfFileMend class

يمثل فئة لإضافة النصوص والصور على صفحات مستند PDF الموجود.

نوع PdfFileMend يعرض الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| PdfFileMend() | منشئ. |
| PdfFileMend(input_file_name, output_file_name) | يُنشئ مثيلاً جديداً من فئة PdfFileMend |
| PdfFileMend(input_stream, output_stream) | يُنشئ مثيلاً جديداً من فئة PdfFileMend |
| PdfFileMend(document) | يُنشئ مثيلاً جديداً من فئة PdfFileMend |
| PdfFileMend(document, output_file_name) | يُنشئ مثيلاً جديداً من فئة PdfFileMend |
| PdfFileMend(document, dest_stream) | يُنشئ مثيلاً جديداً من فئة PdfFileMend |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| مستند | يحصل على واجهة المستند التي يعمل عليها. |
| input_stream | يضبط تدفق الإدخال. |
| output_stream | يضبط تدفق الإخراج. |
| input_file | يضبط ملف الإدخال. |
| output_file | يضبط ملف الإخراج. |
| wrap_mode | يضبط أو يحصل على خوارزمية التفاف الكلمات. راجع WordWrapMode و IsWordWrap. |
| text_positioning_mode | يضبط أو يحصل على استراتيجية تموضع النص. [PositioningMode](/pdf/python-net/aspose.pdf.facades/positioningmode/)<br/>            الوضع الافتراضي هو Legacy. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| bind_pdf(src_file) | يربط مستند PDF للتحرير. |
| bind_pdf(src_stream) | يربط مستند PDF للتحرير. |
| bind_pdf(src_doc) | يربط مستند PDF للتحرير. |
| save(dest_file) | يحفظ مستند PDF إلى الملف المحدد. |
| save(dest_stream) | يحفظ مستند PDF إلى الدفق المحدد. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | يضيف الصورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | يضيف الصورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | يضيف الصورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | يضيف الصورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | يضيف الصورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | يضيف الصورة إلى الصفحة المحددة من مستند PDF عند الإحداثيات المحددة. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | يضيف الصورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | يضيف الصورة إلى الصفحات المحددة من مستند PDF عند الإحداثيات المحددة. |
| add_text(text, page_num, lower_left_x, lower_left_y) | غير مُنفّذ. |
| add_text(text, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | غير مُنفّذ. |
| add_text(text, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | غير مُنفّذ. |
| close() | يغلق كائن PdfFileMend. |

### انظر أيضًا

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

