---
title: "PdfExtractor"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "فئة لاستخراج الصور والنص من مستند PDF."
type: docs
weight: 210
url: /ar/python-net/aspose.pdf.facades/pdfextractor/
---

## PdfExtractor class

فئة لاستخراج الصور والنص من مستند PDF.

يعرض نوع PdfExtractor الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| PdfExtractor() | ينشئ كائنًا جديدًا من نوع [PdfExtractor](/pdf/python-net/aspose.pdf.facades/pdfextractor/). |
| PdfExtractor(document) | ينشئ مثيلًا جديدًا من فئة PdfExtractor |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| مستند | يحصل على واجهة المستند التي يعمل عليها. |
| start_page | يحصل أو يعيّن صفحة البداية في نطاق الصفحات حيث سيتم تنفيذ عملية الاستخراج. |
| end_page | يحصل أو يعيّن صفحة النهاية في نطاق الصفحات حيث سيتم تنفيذ عملية الاستخراج. |
| extract_text_mode | يعيّن الوضع لنتيجة استخراج النص. |
| text_search_options | يحصل أو يضبط خيارات بحث النص. |
| extract_image_mode | يعيّن الوضع لعملية استخراج الصور. |
| is_bidi | يكون صحيحًا عندما يحتوي النص على رموز عبرية أو عربية. يجب أخذ هذه الحالة في الاعتبار بشكل خاص لأن<br/>            وظائف السلسلة تغير سلوكها وتبدأ معالجة النص من اليمين إلى اليسار (باستثناء الأرقام <br/>            وغيرها من الأحرف غير النصية). |
| resolution | يعيّن أو يحصل على الدقة للصور المستخرجة.<br/>            القيمة الافتراضية هي 150.<br/>            الصور التي لها قيمة دقة أعلى تكون أكثر وضوحًا.<br/>            ومع ذلك فإن زيادة قيمة الدقة يؤدي إلى زيادة الوقت والذاكرة المطلوبة لاستخراج الصور.<br/>            عادةً للحصول على صورة واضحة يكفي تعيين الدقة إلى 150 أو 300. |
| password | يحصل أو يعيّن كلمة مرور الملف المدخل. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| bind_pdf(input_file) | ربط ملف PDF المدخل. |
| bind_pdf(input_stream) | يربط مستند PDF من الدفق. |
| bind_pdf(src_doc) | يُهيئ الـ facade. |
| extract_text() | يستخرج النص من مستند PDF باستخدام ترميز Unicode. |
| extract_text(encoding) | يستخرج النص من مستند PDF باستخدام الترميز المحدد. |
| get_text(output_file) | يحفظ النص إلى ملف. انظر أيضًا:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream) | يحفظ النص إلى دفق. انظر أيضًا:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream, filter_not_ascii) | يحفظ النص إلى دفق. انظر أيضًا:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_next_image(output_file) | يسترجع الصورة التالية من مستند PDF. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة. |
| get_next_image(output_file, format) | يسترجع الصورة التالية من مستند PDF بالتنسيق المحدد. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة. |
| get_next_image(output_stream, format) | يسترجع الصورة التالية من ملف PDF ويخزنها في دفق بالتنسيق المحدد. |
| get_next_image(output_stream) | يسترجع الصورة التالية من ملف PDF ويخزنها في دفق بالتنسيق المحدد. |
| extract_attachment() | يستخرج المرفقات من مستند PDF. |
| extract_attachment(attachment_file_name) | يستخرج المرفق إلى ملف PDF حسب اسم المرفق. |
| get_next_page_text(output_file) | يحفظ نص صفحة واحدة إلى ملف. |
| get_next_page_text(output_stream) | يحفظ نص صفحة واحدة إلى تدفق. |
| close() | يتخلص من Aspose.Pdf.Document المرتبط بواجهة. |
| extract_image() | استخراج الصور من ملف PDF. |
| has_next_image() | يتحقق مما إذا كانت هناك صور إضافية يمكن الوصول إليها في مستند PDF. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة. |
| get_attach_names() | يعيد قائمة بالمرفقات في ملف PDF. ملاحظة: يجب استدعاء ExtractAttachments قبل استخدام هذه الطريقة. |
| get_attachment(output_path) | يخزن المرفق في ملف. |
| has_next_page_text() | يشير إلى ما إذا كان يمكن الحصول على مزيد من النصوص أم لا. |
| get_attachment_info() | يحصل على قائمة المرفقات. |

### انظر أيضًا

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

