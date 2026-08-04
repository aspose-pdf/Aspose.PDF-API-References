---
title: "PdfPageEditor"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يمثل فئة لتعديل صفحة ملف PDF، بما في ذلك تدوير الصفحة، تكبير الصفحة، نقل الموقع وتغيير حجم الصفحة."
type: docs
weight: 340
url: /ar/python-net/aspose.pdf.facades/pdfpageeditor/
---

## PdfPageEditor class

يمثل فئة لتعديل صفحة ملف PDF، بما في ذلك تدوير الصفحة، تكبير الصفحة، نقل الموقع وتغيير حجم الصفحة.

نوع PdfPageEditor يعرض الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| PdfPageEditor() | منشئ لفئة PdfPageEditor. |
| PdfPageEditor(document) | يُنشئ مثلاً جديداً من فئة PdfPageEditor |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| مستند | يحصل على واجهة المستند التي يعمل عليها. |
| transition_duration | يحصل أو يضبط مدة تأثير الانتقال. |
| transition_type | يحصل أو يضبط نمط الانتقال لاستخدامه عند الانتقال إلى هذه الصفحة من أخرى أثناء العرض. |
| display_duration | يحصل أو يضبط مدة العرض للصفحات. |
| process_pages | يحصل أو يضبط أرقام الصفحات التي سيتم تحريرها. بشكل افتراضي، سيتم تحرير كل صفحة. |
| rotation | يحصل أو يضبط دوران الصفحات، يجب أن يكون الدوران 0 أو 90 أو 180 أو 270.<br/>            القيمة الافتراضية هي 0. |
| zoom | الحصول أو تعيين معامل التكبير. القيمة 1.0 تعادل 100٪.<br/>            القيمة الافتراضية هي 1.0. |
| page_size | الحصول أو تعيين حجم صفحة ملف الإخراج. |
| المحاذاة | الحصول أو تعيين محاذاة أفقية لمحتوى PDF الأصلي على صفحة النتيجة، القيمة الافتراضية هي AlignmentType.Left. |
| horizontal_alignment | الحصول أو تعيين محاذاة أفقية لمحتوى PDF الأصلي على صفحة النتيجة، القيمة الافتراضية هي AlignmentType.Left. |
| vertical_alignment | الحصول أو تعيين محاذاة رأسية لمحتوى PDF الأصلي على صفحة النتيجة، القيمة الافتراضية هي VerticalAlignmentType.Bottom. |
| vertical_alignment_type | الحصول أو تعيين محاذاة رأسية لمحتوى PDF الأصلي على صفحة النتيجة، القيمة الافتراضية هي VerticalAlignmentType.Bottom. |
| SPLITVOUT | تقسيم عمودي خارجي |
| SPLITHOUT | تقسيم أفقي خارجي |
| SPLITVIN | تقسيم عمودي داخلي |
| SPLITHIN | تقسيم أفقي داخلي |
| BLINDV | ستائر عمودية |
| BLINDH | ستائر عمودية |
| INBOX | صندوق داخلي |
| OUTBOX | صندوق خارجي |
| LRWIPE | مسح من اليسار إلى اليمين |
| RLWIPE | مسح من اليمين إلى اليسار |
| BTWIPE | مسح من الأسفل إلى الأعلى |
| TBWIPE | مسح من الأعلى إلى الأسفل |
| DISSOLVE | الصفحة القديمة تتلاشى |
| LRGLITTER | بريق من اليسار إلى اليمين |
| TBGLITTER | بريق من الأعلى إلى الأسفل |
| DGLITTER | بريق قطري |
## الطرق
| الاسم | الوصف |
| :- | :- |
| bind_pdf(src_file) | يربط مستند PDF للتحرير. |
| bind_pdf(src_stream) | يربط مستند PDF للتحرير. |
| bind_pdf(src_doc) | يربط مستند PDF للتحرير. |
| save(output_file) | يحفظ المستند المعدل في ملف. |
| save(output_stream) | يحفظ المستند المعدل في تدفق. |
| close() | يطلق أي موارد مرتبطة بالواجهة الحالية. |
| move_position(move_x, move_y) | ينقل الأصل من (0, 0) إلى النقطة المحددة. <br/>            الأصل هو أسفل اليسار والوحدة هي النقطة(1 بوصة = 72 نقطة). |
| get_pages() | يعيد العدد الإجمالي للصفحات. |
| get_page_size(page) | يعيد حجم الصفحة للصفحة المحددة. |
| get_page_rotation(page) | يعيد دوران الصفحة المحددة. |
| get_page_box_size(page, page_box_name) | يعيد حجم الصندوق المحدد في المستند. |
| apply_changes() | تطبيق التغييرات التي تم إجراؤها على صفحات المستند. |

### انظر أيضًا

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

