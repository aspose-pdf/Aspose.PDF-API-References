---
title: "PdfContentEditor"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يمثل فئة لتحرير محتوى ملف PDF."
type: docs
weight: 190
url: /ar/python-net/aspose.pdf.facades/pdfcontenteditor/
---

## PdfContentEditor class

يمثل فئة لتحرير محتوى ملف PDF.

يعرض نوع PdfContentEditor الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| PdfContentEditor() | المُنشئ لكائن PdfContentEditor. |
| PdfContentEditor(document) | يُنشئ نسخة جديدة من فئة PdfContentEditor |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| مستند | يحصل على واجهة المستند التي يعمل عليها. |
| text_search_options | يحصل أو يضبط خيارات بحث النص. |
| text_edit_options | يحصل أو يضبط خيارات تحرير النص. |
| text_replace_options | يحصل أو يضبط خيارات استبدال النص. |
| replace_text_strategy | مجموعة من المعلمات لعملية استبدال النص |
| DOCUMENT_OPEN | نوع حدث المستند. يفتح مستندًا. |
| DOCUMENT_CLOSE | نوع حدث المستند. يغلق مستندًا. |
| DOCUMENT_WILL_SAVE | نوع حدث المستند. ينفّذ إجراءً قبل الحفظ. |
| DOCUMENT_SAVED | نوع حدث المستند. ينفّذ إجراءً بعد الحفظ. |
| DOCUMENT_WILL_PRINT | نوع حدث المستند. ينفّذ إجراءً قبل الطباعة. |
| DOCUMENT_PRINTED | نوع حدث المستند. تنفيذ إجراء بعد الطباعة. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| bind_pdf(input_file) | يربط ملف PDF للتحرير. |
| bind_pdf(input_stream) | يربط تدفق PDF للتحرير. |
| bind_pdf(src_doc) | يربط مستند PDF للتحرير. |
| save(dest_file) | يحفظ مستند PDF إلى الملف المحدد. |
| save(dest_stream) | يحفظ مستند PDF إلى الدفق المحدد. |
| create_web_link(rect, url, original_page, clr) | ينشئ رابط ويب في مستند PDF. |
| create_web_link(rect, url, original_page) | ينشئ رابط ويب في مستند PDF. |
| create_local_link(rect, des_page, original_page, clr) | ينشئ رابطًا محليًا في مستند PDF. |
| create_local_link(rect, des_page, original_page) | ينشئ رابطًا محليًا في مستند PDF. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page, clr) | ينشئ رابطًا إلى صفحة أخرى في مستند PDF. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page) | ينشئ رابطًا إلى صفحة أخرى في مستند PDF. |
| create_application_link(rect, application, page, clr) | ينشئ رابطًا لتشغيل تطبيق في مستند PDF. |
| create_application_link(rect, application, page) | ينشئ رابطًا لتشغيل تطبيق في مستند PDF. |
| create_file_attachment(rect, contents, file_path, page, name) | ينشئ توضيح مرفق ملف. |
| create_file_attachment(rect, contents, file_path, page, name, opacity) | ينشئ توضيح مرفق ملف. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name) | ينشئ توضيح مرفق ملف. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name, opacity) | ينشئ توضيح مرفق ملف. |
| add_document_attachment(file_attachment_path, description) | يضيف مرفق مستند دون توضيح. |
| add_document_attachment(file_attachment_stream, file_attachment_name, description) | يضيف مرفق مستند دون توضيح. |
| create_rubber_stamp(page, annot_rect, icon, annot_contents, color) | ينشئ توضيح ختم مطاطي. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_file) | ينشئ توضيح ختم مطاطي. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_stream) | ينشئ توضيح ختم مطاطي. |
| delete_image(page_number, index) | يحذف الصور المحددة في الصفحة المحددة. |
| delete_image() | يحذف الصور المحددة في الصفحة المحددة. |
| replace_text(src_string, the_page, dest_string, text_state) | يستبدل النص في ملف PDF في الصفحة المحددة. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) يمكن تحديد كائن (عائلة الخط، اللون) لاستبدال النص. |
| replace_text(src_string, dest_string) | يستبدل النص في ملف PDF في الصفحة المحددة. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) يمكن تحديد كائن (عائلة الخط، اللون) لاستبدال النص. |
| replace_text(src_string, the_page, dest_string) | يستبدل النص في ملف PDF في الصفحة المحددة. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) يمكن تحديد كائن (عائلة الخط، اللون) لاستبدال النص. |
| replace_text(src_string, dest_string, text_state) | يستبدل النص في ملف PDF في الصفحة المحددة. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) يمكن تحديد كائن (عائلة الخط، اللون) لاستبدال النص. |
| replace_text(src_string, dest_string, font_size) | يستبدل النص في ملف PDF في الصفحة المحددة. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) يمكن تحديد كائن (عائلة الخط، اللون) لاستبدال النص. |
| delete_stamp_by_ids(stamp_ids) | يحذف الطوابع ذات المعرفات المحددة من جميع صفحات المستند. |
| delete_stamp_by_ids(page_number, stamp_ids) | يحذف الطوابع ذات المعرفات المحددة من جميع صفحات المستند. |
| delete_stamp_by_id(page_number, stamp_id) | يحذف الطوابع ذات المعرفات المحددة من جميع صفحات المستند. |
| delete_stamp_by_id(stamp_id) | يحذف الطوابع ذات المعرفات المحددة من جميع صفحات المستند. |
| close() | يغلق المستند المفتوح. |
| extract_link() | يستخرج مجموعة كائنات Link الموجودة في مستند PDF. |
| create_java_script_link(code, rect, original_page, color) | ينشئ رابطًا إلى JavaScript في مستند PDF. |
| create_text(rect, title, contents, open, icon, page) | ينشئ تعليقة نصية في مستند PDF |
| create_free_text(rect, contents, page) | ينشئ تعليقة نص حر في مستند PDF |
| create_markup(rect, contents, type, page, clr) | ينشئ تعليقة توصيفية في مستند PDF. |
| create_popup(rect, contents, open, page) | ينشئ تعليقة منبثقة في مستند PDF. |
| delete_attachments() | يحذف جميع المرفقات في مستند PDF. |
| create_line(rect, contents, x1, y1, x2, y2, page, border, clr, border_style, dash_array, le_array) | ينشئ تعليقا على الخط. |
| create_square_circle(rect, contents, clr, square, page, border_width) | ينشئ تعليقا على الشكل المربع-الدائري. |
| draw_curve(line_info, page, annot_rect, annot_contents) | ينشئ تعليقا على المنحنى. |
| create_polygon(line_info, page, annot_rect, annot_contents) | ينشئ تعليقا على المضلع. |
| create_poly_line(line_info, page, annot_rect, annot_contents) | ينشئ تعليقا على الخط المتعدد. |
| create_caret(page, annot_rect, caret_rect, symbol, annot_contents, color) | ينشئ تعليقا على المؤشر. |
| create_bookmarks_action(title, color, bold_flag, italic_flag, file, action_type, destination) | ينشئ إشارة مرجعية بالإجراء المحدد. |
| add_document_additional_action(event_type, code) | يضيف إجراءً إضافيًا لحدث المستند. |
| remove_document_open_action() | يزيل إجراء الفتح من المستند. هذه العملية مفيدة عند دمج مستندات متعددة تستخدم إجراء 'GoTo' صريح عند بدء التشغيل. |
| change_viewer_preference(viewer_attribution) | يغيّر تفضيل العرض. |
| get_viewer_preference() | يعيد تفضيل العرض. |
| replace_image(page_number, index, image_file) | يستبدل الصورة المحددة في الصفحة المحددة من مستند PDF بصورة أخرى. |
| create_movie(rect, file_path, page) | ينشئ تعليقات الفيلم. |
| create_sound(rect, file_path, name, page, rate) | ينشئ تعليقات صوتية. |
| delete_stamp(page_number, index) | يحذف عدة طوابع على الصفحة المحددة باستخدام فهارس الطوابع. |
| hide_stamp_by_id(page_number, stamp_id) | يخفي الطابع. بعد الإخفاء، قد يتم استعادة رؤية الطابع باستخدام طريقة ShowStampById. |
| show_stamp_by_id(page_number, stamp_id) | يعرض الطابع الذي تم إخفاؤه بواسطة HiddenStampById. |
| move_stamp_by_id(page_number, stamp_id, x, y) | يغيّر موضع الطابع على الصفحة. |
| move_stamp(page_number, stamp_index, x, y) | يغيّر موضع الطابع على الصفحة. |
| get_stamps(page_number) | يعيد مصفوفة من الطوابع على الصفحة. |

### انظر أيضًا

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

