---
title: "PdfConverter"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يمثل فئة لتحويل كل صفحة من ملف pdf إلى صور، يدعم الآن صيغ BMP و JPEG و PNG و TIFF.<br/>            المحتوى المدعوم في ملفات pdf يشمل الصور والنماذج والتعليقات."
type: docs
weight: 200
url: /ar/python-net/aspose.pdf.facades/pdfconverter/
---

## PdfConverter class

يمثل فئة لتحويل كل صفحة من ملف PDF إلى صور، يدعم الآن BMP و JPEG و PNG و TIFF.<br/>            المحتوى المدعوم في ملفات PDF: الصور، النماذج، التعليقات.

يعرض نوع PdfConverter الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| PdfConverter() | ينشئ كائنًا جديدًا من [PdfConverter](/pdf/python-net/aspose.pdf.facades/pdfconverter/). |
| PdfConverter(document) | ينشئ نسخة جديدة من فئة PdfConverter |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| مستند | يحصل على واجهة المستند التي يعمل عليها. |
| coordinate_type | يحصل أو يضبط نوع إحداثيات الصفحة (صناديق Media/Crop). يتم استخدام قيمة CropBox كإعداد افتراضي. |
| show_hidden_areas | يحصل أو يضبط العلامة التي تتحكم في إظهار المناطق المخفية على الصفحة. |
| rendering_options | يحصل أو يضبط خيارات العرض. |
| form_presentation_mode | يحصل أو يضبط وضع عرض النموذج. |
| resolution | يحصل أو يضبط الدقة أثناء التحويل. كلما ارتفعت الدقة، كلما كان سرعة التحويل أبطأ. القيمة الافتراضية هي 150. |
| start_page | يحصل أو يعيّن موضع البداية الذي تريد تحويله. القيمة الدنيا هي 1. |
| end_page | يحصل أو يعيّن موضع النهاية الذي تريد تحويله. |
| password | يحصل أو يعيّن OwnerPassword للمستند. |
| user_password | يحصل أو يعيّن UserPassword للمستند. |
| page_count | يحصل على عدد الصفحات. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| bind_pdf(input_file) | يربط ملف Pdf للتحويل. |
| bind_pdf(input_stream) | يربط تدفق Pdf للتحويل. |
| bind_pdf(src_doc) | يُهيئ الـ facade. |
| save_as_tiff(output_file) | يحوّل كل صفحات مستند pdf إلى صور ويحفظ الصور في ملف TIFF واحد. |
| save_as_tiff(output_file, compression_type) | يحوّل كل صفحات مستند pdf إلى صور ويحفظ الصور في ملف TIFF واحد. |
| save_as_tiff(output_file, image_width, image_height) | يحوّل كل صفحات مستند pdf إلى صور بالأبعاد، ويحفظ الصور في ملف TIFF واحد. |
| save_as_tiff(output_file, page_size) | يحوّل كل صفحات مستند pdf إلى صور بحجم الصفحة، ويحفظ الصور في ملف TIFF واحد. |
| save_as_tiff(output_file, page_size, settings) | يحوّل كل صفحات مستند pdf إلى صور بحجم الصفحة، ويحفظ الصور في ملف TIFF واحد. |
| save_as_tiff(output_file, image_width, image_height, compression_type) | يحوّل كل صفحات مستند pdf إلى صور بالأبعاد، ويحفظ الصور في ملف TIFF واحد. |
| save_as_tiff(output_file, image_width, image_height, settings) | يحوّل كل صفحات مستند pdf إلى صور بالأبعاد، ويحفظ الصور في ملف TIFF واحد. |
| save_as_tiff(output_file, image_width, image_height, settings, converter) | يحوّل كل صفحات مستند pdf إلى صور بالأبعاد، ويحفظ الصور في ملف TIFF واحد. |
| save_as_tiff(output_stream) | يحوّل كل صفحات مستند pdf إلى صور ويحفظ الصور في تدفق ClassF TIFF واحد. |
| save_as_tiff(output_stream, compression_type) | يحوّل كل صفحات مستند pdf إلى صور ويحفظ الصور في ملف TIFF واحد. |
| save_as_tiff(output_stream, page_size) | يحوّل كل صفحات مستند pdf إلى صور ويحفظ الصور في تدفق ClassF TIFF واحد. |
| save_as_tiff(output_stream, page_size, settings) | يقوم بتحويل كل صفحة من مستند PDF إلى صور بحجم الصفحة ويحفظ الصور في تدفق TIFF واحد. |
| save_as_tiff(output_stream, image_width, image_height) | يحوّل كل صفحات مستند pdf إلى صور ويحفظ الصور في تدفق ClassF TIFF واحد. |
| save_as_tiff(output_stream, image_width, image_height, compression_type) | يقوم بتحويل كل صفحة من مستند PDF إلى صور بالأبعاد، ويحفظ الصور في تدفق TIFF واحد. |
| save_as_tiff(output_stream, image_width, image_height, settings) | يقوم بتحويل كل صفحة من مستند PDF إلى صور بالأبعاد، ويحفظ الصور في تدفق TIFF واحد. |
| save_as_tiff(output_stream, image_width, image_height, settings, converter) | يقوم بتحويل كل صفحة من مستند PDF إلى صور بالأبعاد، ويحفظ الصور في تدفق TIFF واحد. |
| save_as_tiff(output_file, settings) | يحوّل كل صفحات مستند pdf إلى صور بحجم الصفحة، ويحفظ الصور في ملف TIFF واحد. |
| save_as_tiff(output_file, settings, converter) | يحوّل كل صفحات مستند pdf إلى صور بالأبعاد، ويحفظ الصور في ملف TIFF واحد. |
| save_as_tiff(output_stream, settings) | يقوم بتحويل كل صفحة من مستند PDF إلى صور بحجم الصفحة ويحفظ الصور في تدفق TIFF واحد. |
| save_as_tiff(output_stream, settings, converter) | يقوم بتحويل كل صفحة من مستند PDF إلى صور بالأبعاد، ويحفظ الصور في تدفق TIFF واحد. |
| save_as_tiff_class_f(output_file, image_width, image_height) | يقوم بتحويل كل صفحة من مستند PDF إلى صور ويحفظ الصور في ملف TIFF ClassF واحد. |
| save_as_tiff_class_f(output_file, page_size) | يقوم بتحويل كل صفحة من مستند PDF إلى صور ويحفظ الصور في ملف TIFF ClassF واحد. |
| save_as_tiff_class_f(output_stream, image_width, image_height) | يحوّل كل صفحات مستند pdf إلى صور ويحفظ الصور في تدفق ClassF TIFF واحد. |
| save_as_tiff_class_f(output_stream, page_size) | يحوّل كل صفحات مستند pdf إلى صور ويحفظ الصور في تدفق ClassF TIFF واحد. |
| save_as_tiff_class_f(output_file) | يقوم بتحويل كل صفحة من مستند PDF إلى صور ويحفظ الصور في ملف TIFF ClassF واحد. |
| save_as_tiff_class_f(output_stream) | يحوّل كل صفحات مستند pdf إلى صور ويحفظ الصور في تدفق ClassF TIFF واحد. |
| get_next_image(output_file) | يحفظ الصورة إلى ملف باستخدام تنسيق الصورة الافتراضي - jpeg. |
| get_next_image(output_file, page_size) | يحفظ الصورة إلى ملف بحجم الصفحة المحدد وتنسيق الصورة الافتراضي - jpeg. |
| get_next_image(output_file, format) | يحفظ الصورة إلى ملف باستخدام تنسيق الصورة المحدد. |
| get_next_image(output_file, page_size, format) | يحفظ الصورة إلى ملف بحجم الصفحة المحدد وتنسيق الصورة. |
| get_next_image(output_stream) | يحفظ الصورة إلى التدفق باستخدام تنسيق الصورة الافتراضي - jpeg. |
| get_next_image(output_stream, page_size) | يحفظ الصورة إلى التدفق باستخدام حجم الصفحة المحدد. |
| get_next_image(output_stream, format) | يحفظ الصورة إلى التدفق باستخدام تنسيق الصورة المحدد. |
| get_next_image(output_stream, page_size, format) | يحفظ الصورة إلى التدفق باستخدام حجم الصفحة المحدد. |
| get_next_image(output_file, format, image_width, image_height, quality) | يحفظ الصورة إلى ملف باستخدام تنسيق الصورة المحدد، الأبعاد والجودة. |
| get_next_image(output_stream, format, image_width, image_height, quality) | يحفظ الصورة إلى التدفق باستخدام تنسيق الصورة المعطى، الأبعاد والجودة. |
| get_next_image(output_file, format, image_width, image_height, quality) | يحفظ الصورة إلى ملف باستخدام تنسيق الصورة المعطى، حجم الصورة، والجودة. |
| get_next_image(output_stream, format, image_width, image_height, quality) | يحفظ الصورة إلى التدفق باستخدام تنسيق الصورة المعطى، الحجم والجودة. |
| get_next_image(output_file, format, image_width, image_height) | يحفظ الصورة إلى ملف باستخدام تنسيق الصورة المحدد، الأبعاد والجودة. |
| get_next_image(output_stream, format, image_width, image_height) | يحفظ الصورة إلى التدفق باستخدام تنسيق الصورة المعطى، الأبعاد والجودة. |
| get_next_image(output_stream, format, quality) | يحفظ الصورة إلى التدفق باستخدام تنسيق الصورة المعطى، الأبعاد والجودة. |
| get_next_image(output_stream, page_size, format, quality) | يحفظ الصورة إلى التدفق باستخدام حجم الصفحة المحدد، تنسيق الصورة والجودة. |
| get_next_image(output_file, format, quality) | يحفظ الصورة إلى ملف باستخدام تنسيق الصورة المحدد، الأبعاد والجودة. |
| get_next_image(output_file, page_size, format, quality) | يحفظ الصورة إلى ملف باستخدام حجم الصفحة المحدد، تنسيق الصورة والجودة. |
| close() | أغلق نسخة PdfConverter وحرّر الموارد. |
| do_convert() | قم ببعض الأعمال الأولية لتحويل مستند pdf إلى صور. |
| has_next_image() | يشير إلى ما إذا كان ملف PDF يحتوي على المزيد من الصور أم لا. |
| merge_images(input_images_streams, output_image_format, merge_mode, horizontal, vertical) | لا شيء |
| merge_images_as_tiff(input_images_streams) | يقوم بدمج قائمة تدفقات TIFF كتيار TIFF متعدد الإطارات. |

### انظر أيضًا

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

