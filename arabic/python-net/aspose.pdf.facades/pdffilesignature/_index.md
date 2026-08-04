---
title: "PdfFileSignature"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يمثل فئة لتوقيع ملف PDF باستخدام شهادة."
type: docs
weight: 310
url: /ar/python-net/aspose.pdf.facades/pdffilesignature/
---

## PdfFileSignature class

يمثل فئة لتوقيع ملف PDF باستخدام شهادة.

يعرض نوع PdfFileSignature الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| PdfFileSignature() | المُنشئ لفئة PdfFileSignature. |
| PdfFileSignature(input_file) | ينشئ مثلاً جديداً من فئة PdfFileSignature |
| PdfFileSignature(input_file, output_file) | ينشئ مثلاً جديداً من فئة PdfFileSignature |
| PdfFileSignature(document) | ينشئ مثلاً جديداً من فئة PdfFileSignature |
| PdfFileSignature(document, output_file) | ينشئ مثلاً جديداً من فئة PdfFileSignature |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| مستند | يحصل على واجهة المستند التي يعمل عليها. |
| signature_appearance | يضبط أو يحصل على مظهر رسومي للتوقيع. قيمة الخاصية تمثل اسم ملف الصورة. |
| is_ltv_enabled | يحصل على علم تمكين LTV. |
| is_certified | يحصل على العلم الذي يحدد ما إذا كان المستند مُصدّقاً أم لا. |
| signature_appearance_stream | يضبط أو يحصل على مظهر رسومي للتوقيع. قيمة الخاصية تمثل تدفق الصورة. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| bind_pdf(input_file) | يربط ملف Pdf للتحرير. |
| bind_pdf(input_stream) | يربط تدفق Pdf للتحرير. |
| bind_pdf(src_doc) | يربط مستند PDF للتحرير. |
| save(output_file) | يحفظ ملف PDF الناتج إلى ملف. |
| save(output_stream) | يحفظ ملف PDF الناتج إلى تدفق. |
| save() | يحفظ ملف PDF الناتج إلى ملف. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect) | إنشاء توقيع على مستند pdf. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | وقّع المستند باستخدام توقيع النوع المحدد. |
| sign(page, visible, annot_rect, sig) | وقّع المستند باستخدام توقيع النوع المحدد. |
| sign(sig_name, sig_reason, sig_contact, sig_location, sig) | وقّع المستند باستخدام توقيع النوع المحدد. |
| sign(page, sig_name, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | وقّع المستند باستخدام توقيع النوع المحدد. |
| sign(sig_name, sig) | وقّع المستند باستخدام توقيع النوع المحدد. |
| certify(page, sig_reason, sig_contact, sig_location, visible, annot_rect, doc_mdp_signature) | صادق على المستند باستخدام توقيع MDP.<br/>            يجب توفير بيانات مثل سبب التوقيع، جهة الاتصال والموقع عبر الخصائص المقابلة لكائن Signature sig. |
| certify(sig_name, doc_mdp_signature) | صادق على المستند باستخدام توقيع MDP.<br/>            يجب توفير بيانات مثل سبب التوقيع، جهة الاتصال والموقع عبر الخصائص المقابلة لكائن Signature sig. |
| remove_signature(sign_name) | إزالة التوقيع وفقًا لاسم التوقيع. |
| remove_signature(sign_name, remove_field) | يزيل التوقيع وفقًا لاسم التوقيع. |
| close() | يغلق الواجهة. |
| get_access_permissions() | يرجع قيمة أذونات الوصول للمستند المصدق باستخدام نوع توقيع MDP. |
| get_sign_names(only_active) | يحصل على أسماء جميع التوقيعات غير الفارغة. |
| get_blank_sign_names() | يحصل على أسماء جميع حقول التوقيع الفارغة. |
| is_contain_signature() | يتحقق مما إذا كان ملف pdf يحتوي على توقيع رقمي أم لا. |
| contains_signature() | يتحقق مما إذا كان ملف pdf يحتوي على توقيع رقمي أم لا. |
| contains_usage_rights() | يتحقق مما إذا كان ملف PDF يحتوي على حقوق الاستخدام أم لا. |
| is_covers_whole_document(sign_name) | يتحقق مما إذا كانت التوقيع تغطي المستند بالكامل. |
| covers_whole_document(sign_name) | يتحقق مما إذا كانت التوقيع تغطي المستند بالكامل. |
| get_revision(sign_name) | يحصل على إصدار التوقيع. |
| get_total_revision() | يحصل على الإصدار الإجمالي. |
| remove_usage_rights() | يزيل إدخال حقوق الاستخدام. |
| verify_signed(sign_name) | يتحقق من صحة التوقيع. |
| get_signer_name(sign_name) | يحصل على اسم الشخص أو المؤسسة التي توقّع مستند PDF. |
| get_date_time(sign_name) | يحصل على تاريخ ووقت التوقيع. |
| get_reason(sign_name) | يحصل على سبب التوقيع. |
| get_location(sign_name) | يحصل على موقع التوقيع. |
| get_contact_info(sign_name) | يحصل على معلومات الاتصال الخاصة بالتوقيع. |
| verify_signature(sign_name) | يتحقق من صحة التوقيع. |
| extract_image(sign_name) | يستخرج صورة التوقيع. |
| extract_certificate(sign_name) | يستخرج شهادة X.509 الفردية للتوقيع كتيار. |
| set_certificate(pfx, pass) | تعيين ملف الشهادة وكلمة المرور لإجراء التوقيع. |

### انظر أيضًا

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

