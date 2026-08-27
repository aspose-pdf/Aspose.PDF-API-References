---
title: "PdfBookmarkEditor"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يمثل فئة للعمل مع إشارات مرجعية لملف PDF بما في ذلك الإنشاء، التعديل، التصدير، الاستيراد والحذف."
type: docs
weight: 180
url: /ar/python-net/aspose.pdf.facades/pdfbookmarkeditor/
---

## PdfBookmarkEditor class

يمثل فئة للعمل مع إشارات مرجعية لملف PDF بما في ذلك الإنشاء، التعديل، التصدير، الاستيراد والحذف.

نوع PdfBookmarkEditor يعرض الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| PdfBookmarkEditor() | يُنشئ كائنًا جديدًا من [PdfBookmarkEditor](/pdf/python-net/aspose.pdf.facades/pdfbookmarkeditor/). |
| PdfBookmarkEditor(document) | يُنشئ مثيلًا جديدًا لفئة PdfBookmarkEditor |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| مستند | يحصل على واجهة المستند التي يعمل عليها. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| bind_pdf(src_file) | يربط مستند PDF للتحرير. |
| bind_pdf(src_stream) | يربط مستند PDF للتحرير. |
| bind_pdf(src_doc) | يربط مستند PDF للتحرير. |
| save(dest_file) | يحفظ مستند PDF إلى الملف المحدد. |
| save(dest_stream) | يحفظ مستند PDF إلى الدفق المحدد. |
| create_bookmarks() | ينشئ إشارات مرجعية لجميع الصفحات. |
| create_bookmarks(bookmark) | ينشئ إشارات مرجعية لجميع الصفحات. |
| create_bookmarks(color, bold_flag, italic_flag) | إنشاء إشارات مرجعية لجميع الصفحات باللون والنمط المحددين (غامق، مائل). |
| create_bookmark_of_page(bookmark_name, page_number) | ينشئ إشارة مرجعية للصفحة المحددة. |
| create_bookmark_of_page(bookmark_name, page_number) | ينشئ إشارات مرجعية للصفحات المحددة. |
| delete_bookmarks() | يحذف جميع الإشارات المرجعية لمستند PDF. |
| delete_bookmarks(title) | يحذف إشارة مرجعية لمستند PDF. |
| extract_bookmarks() | يستخرج الإشارات المرجعية لجميع المستويات من المستند. |
| extract_bookmarks(upper_level) | يستخرج الإشارات المرجعية لجميع المستويات من المستند. |
| extract_bookmarks(title) | يستخرج الإشارات المرجعية ذات العنوان المحدد. |
| extract_bookmarks(bookmark) | يستخرج الإشارات المرجعية لجميع المستويات من المستند. |
| export_bookmarks_to_xml(xml_file) | يصدّر الإشارات المرجعية إلى ملف XML. |
| export_bookmarks_to_xml(stream) | يصدّر الإشارات المرجعية إلى تدفق XML. |
| import_bookmarks_with_xml(xml_file) | يستورد الإشارات المرجعية إلى المستند من ملف XML. |
| import_bookmarks_with_xml(stream) | يستورد الإشارات المرجعية إلى المستند من ملف XML. |
| close() | يطلق أي موارد مرتبطة بالواجهة الحالية. |
| modify_bookmarks(s_title, d_title) | يعدّل عنوان الإشارة المرجعية وفقًا للعنوان المحدد. |
| extract_bookmarks_to_html(pdf_file, css_file) | يصدّر الإشارات المرجعية إلى ملف HTML. |
| export_bookmarks_to_html(in_pdf_file, out_html_file) | يصدّر الإشارات المرجعية إلى ملف HTML. |

### انظر أيضًا

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

