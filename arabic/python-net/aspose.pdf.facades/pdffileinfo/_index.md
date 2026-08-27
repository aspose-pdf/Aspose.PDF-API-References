---
title: "PdfFileInfo"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يمثل فئة للوصول إلى المعلومات الوصفية لمستند PDF."
type: docs
weight: 270
url: /ar/python-net/aspose.pdf.facades/pdffileinfo/
---

## PdfFileInfo class

يمثل فئة للوصول إلى المعلومات الوصفية لمستند PDF.

يعرض نوع PdfFileInfo الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| PdfFileInfo() | ينشئ مثيلاً جديداً من الفئة Aspose.Pdf.Facades.PdfFileInfo بالقيم الافتراضية. |
| PdfFileInfo(input_stream) | ينشئ مثيلاً جديداً من الفئة PdfFileInfo |
| PdfFileInfo(input_stream, password) | ينشئ مثيلاً جديداً من الفئة PdfFileInfo |
| PdfFileInfo(input_file) | ينشئ مثيلاً جديداً من الفئة PdfFileInfo |
| PdfFileInfo(input_file, password) | ينشئ مثيلاً جديداً من الفئة PdfFileInfo |
| PdfFileInfo(document) | ينشئ مثيلاً جديداً من الفئة PdfFileInfo |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| مستند | يحصل على واجهة المستند التي يعمل عليها. |
| author | يحصل أو يعيّن معلومات المؤلف للملف PDF. |
| is_encrypted | يتحقق مما إذا كان ملف PDF مشفّراً. |
| is_pdf_file | يتحقق مما إذا كان الإدخال المصدر ملف PDF صالح. |
| use_strict_validation | يستخدم قواعد تحقق صارمة عبر خاصية [is_pdf_file](/pdf/python-net/aspose.pdf.facades/pdffileinfo/). |
| creation_date | يحصل أو يعيّن معلومات CreationDate للملف PDF. |
| creator | يحصل أو يعيّن معلومات Creator للملف PDF. |
| has_collection | يرجع true إذا كان ملف الإدخال الحالي هو ملف 'Portfolio' يحتوي على مجموعة من ملفات PDF داخله. |
| input_file | يحصل أو يعيّن ملف الإدخال. |
| input_stream | يحصل أو يعيّن تدفق الإدخال. |
| keywords | يحصل أو يعيّن معلومات Keywords لوثيقة PDF. |
| mod_date | يحصل أو يعيّن معلومات تاريخ ModDate لوثيقة PDF. |
| number_of_pages | يحصل على عدد صفحات الوثيقة. |
| producer | يحصل على معلومات Producer لوثيقة PDF. |
| subject | يحصل أو يعيّن معلومات Subject لوثيقة PDF. |
| title | يحصل أو يعيّن معلومات Title لوثيقة PDF. |
| password_type | يرجع نوع كلمة المرور التي تم تمريرها لإنشاء كائن PdfFileInfo. راجع القيم الممكنة في [password_type](/pdf/python-net/aspose.pdf.facades/pdffileinfo/).<br/>            انتبه إلى أن مستند PDF يمكن فتحه باستخدام كل من كلمة مرور المستخدم (أو الفتح) وكلمة مرور المالك (أو الأذونات، التحرير). |
| has_open_password | يرجع true إذا كانت كلمة المرور مطلوبة لفتح مستند PDF محمي بكلمة مرور. |
| has_edit_password | يرجع true إذا كانت كلمة المرور مطلوبة لتعديل الأذونات أو خاصية أمان المستند.<br/>            انتبه إلى أن هذه الخاصية يمكن قراءتها فقط إذا تم توفير كلمة مرور صالحة في مُنشئ [PdfFileInfo](/pdf/python-net/aspose.pdf.facades/pdffileinfo/).<br/>            في حالة كون PasswordType غير قابل للوصول (يعني أنه تم توفير كلمة مرور غير صالحة) فإن قراءة هذه الخاصية ستفشل مع [InvalidPasswordException](/pdf/python-net/aspose.pdf/invalidpasswordexception/). |
## الطرق
| الاسم | الوصف |
| :- | :- |
| bind_pdf(src_doc) | يُهيئ الـ facade. |
| bind_pdf(src_file) | يُهيئ الـ facade. |
| bind_pdf(src_stream) | يُهيئ الـ facade. |
| save(dest_stream) | احفظ مستند PDF المحدث في التدفق المحدد. |
| save(dest_file) | احفظ مستند PDF المحدث في الملف المحدد. |
| save_new_info(output_stream) | احفظ مستند PDF المحدث في التدفق المحدد. |
| save_new_info(output_file) | احفظ مستند PDF المحدث في الملف المحدد. |
| close() | يقوم بإلغاء تهيئة المثيل. |
| clear_info() | يمسح جميع معلومات التعريف الخاصة بمستند PDF. |
| get_document_privilege() | يحصل على إعدادات صلاحيات مستند PDF. |
| get_meta_info(name) | يحصل على معلومات مخصصة لمستند PDF باستخدام اسم الخاصية. إذا لم توجد خاصية تطابق الاسم، سيُرجع سلسلة فارغة. |
| get_page_height(page_num) | يحصل على ارتفاع الصفحة المحددة. |
| get_page_rotation(page_num) | يحصل على دوران الصفحة المحددة. |
| get_page_width(page_num) | يحصل على عرض الصفحة المحددة. |
| get_page_x_offset(page_num) | يحصل على الإزاحة الأفقية لمنطقة عرض الصفحة المحددة. |
| get_page_y_offset(page_num) | يحصل على الإزاحة العمودية لمنطقة عرض الصفحة المحددة. |
| get_pdf_version() | يحصل على معلومات إصدار مستند PDF. |
| set_meta_info(name, value) | يضبط معلومات مخصصة لمستند PDF. |
| save_new_info_with_xmp(output_file_name) | يغيّر الخصائص المحددة صراحةً عن طريق ضبط معلومات الملف، بينما تبقى الخصائص الأخرى كما هي. |

### انظر أيضًا

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

