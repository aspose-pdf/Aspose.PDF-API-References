---
title: "FormEditor"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "فئة لتحرير النماذج (إضافة/حذف الحقول وما إلى ذلك)"
type: docs
weight: 110
url: /ar/python-net/aspose.pdf.facades/formeditor/
---

## FormEditor class

فئة لتحرير النماذج (إضافة/حذف الحقول وما إلى ذلك)

نوع FormEditor يعرض الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| FormEditor(src_stream, dest_stream) | يقوم بإنشاء نسخة جديدة من الفئة FormEditor |
| FormEditor(src_file_name, dest_file_name) | يقوم بإنشاء نسخة جديدة من الفئة FormEditor |
| FormEditor() | منشئ لـ FormEditor. |
| FormEditor(document) | يقوم بإنشاء نسخة جديدة من الفئة FormEditor |
| FormEditor(document, dest_file_name) | يقوم بإنشاء نسخة جديدة من الفئة FormEditor |
| FormEditor(document, dest_stream) | يقوم بإنشاء نسخة جديدة من الفئة FormEditor |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| مستند | يحصل على واجهة المستند التي يعمل عليها. |
| src_file_name | يحصل على أو يعيّن اسم ملف المصدر. |
| dest_file_name | يحصل على أو يعيّن اسم ملف الوجهة. |
| src_stream | يحصل على أو يعيّن تدفق المصدر. |
| dest_stream | يحصل على أو يعيّن تدفق الوجهة. |
| العناصر | يضبط العناصر التي ستُضاف إلى صندوق القائمة أو مربع الاختيار الذي تم إنشاؤه حديثًا. |
| export_items | يضبط الخيارات لمربع الاختيار مع قيم التصدير. |
| واجهة | يضبط السمات البصرية للحقل. |
| radio_gap | العضو لتسجيل الفجوة بين زرّي الراديو المتجاورين بالبكسل، القيمة الافتراضية هي 50. |
| radio_horiz | العلم لتحديد ما إذا كانت أزرار الراديو مرتبة أفقيًا أم عموديًا، القيمة الافتراضية هي true. |
| radio_button_item_size | يحصل على أو يعيّن حجم عنصر زر الراديو (عند إضافة حقل زر راديو جديد). |
| submit_flag | يضبط أعلام الإرسال لزر الإرسال |
## الطرق
| الاسم | الوصف |
| :- | :- |
| bind_pdf(src_file) | يربط مستند PDF للتحرير. |
| bind_pdf(src_stream) | يربط مستند PDF للتحرير. |
| bind_pdf(src_doc) | يربط مستند PDF للتحرير. |
| save() | يحفظ التغييرات في ملف الوجهة. |
| save(dest_file) | يحفظ التغييرات في ملف الوجهة. |
| save(dest_stream) | يحفظ التغييرات في ملف الوجهة. |
| add_field(field_type, field_name, page_num, llx, lly, urx, ury) | أضف حقلًا من النوع المحدد إلى النموذج. |
| add_field(field_type, field_name, init_value, page_num, llx, lly, urx, ury) | أضف حقلًا من النوع المحدد إلى النموذج. |
| copy_inner_field(field_name, new_field_name, page_num) | ينسخ حقلًا موجودًا إلى نفس الموضع في رقم الصفحة المحدد.<br/>            سيتم إنشاء مستند جديد يحتوي على كل ما في المستند الأصلي باستثناء الحقل المنسوخ حديثًا. |
| copy_inner_field(field_name, new_field_name, page_num, abscissa, ordinate) | ينسخ حقلًا موجودًا إلى موضع جديد محدد برقم الصفحة والإحداثيات.<br/>            سيتم إنشاء مستند جديد يحتوي على كل ما في المستند الأصلي باستثناء الحقل المنسوخ حديثًا. |
| copy_outer_field(src_file_name, field_name) | ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة الأصلي والإحداثيات.<br/>            ملاحظة: يقتصر على حقول AcroForm (باستثناء مربع الاختيار). |
| copy_outer_field(src_file_name, field_name, page_num) | ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة المحدد والإحداثيات الأصلية.<br/>             ملاحظة: يقتصر على حقول AcroForm (باستثناء مربع الاختيار). |
| copy_outer_field(src_file_name, field_name, page_num, abscissa, ordinate) | ينسخ حقلًا موجودًا من مستند PDF إلى مستند آخر مع رقم الصفحة والإحداثيات المحددة.<br/>            ملاحظة: يقتصر على حقول AcroForm (باستثناء مربع الاختيار). |
| decorate_field(field_name) | يغيّر الخصائص البصرية للحقل المحدد. |
| decorate_field(field_type) | يغيّر الخصائص البصرية لجميع الحقول ذات النوع المحدد. |
| decorate_field() | يغيّر الخصائص البصرية للحقل المحدد. |
| add_list_item(field_name, item_name) | يضيف عنصرًا جديدًا إلى صندوق القائمة. |
| add_list_item(field_name, export_name) | أضف عنصرًا جديدًا بقيمة Export إلى حقل صندوق القائمة الموجود، فقط لحقل صندوق القوائم AcroForm. |
| close() | يغلق الواجهة. |
| set_field_attribute(field_name, flag) | تعيين سمات الحقل. |
| set_field_appearance(field_name, flags) | تعيين علامات الحقل |
| get_field_appearance(field_name) | احصل على علامات الحقل. |
| set_submit_flag(field_name, submit_form_flag) | تعيين علامة الإرسال لزر الإرسال. |
| set_submit_url(field_name, url) | يحدد عنوان URL للزر. |
| set_field_limit(field_name, field_limit) | يحدد الحد الأقصى لعدد الأحرف في حقل النص. |
| set_field_comb_number(field_name, comb_number) | يحدد عدد الفواصل لحقل نص أحادي السطر عادي (يتم <br/>            تقسيم الحقل تلقائيًا إلى عدد متساوٍ من المواقع المتباعدة، أو الفواصل، <br/>            وفقًا لقيمة معامل combNumber). |
| move_field(field_name, llx, lly, urx, ury) | تعيين موضع جديد للحقل. |
| remove_field(field_name) | إزالة الحقل من النموذج. |
| reset_facade() | إعادة تعيين جميع السمات البصرية إلى قيمة فارغة. |
| reset_inner_facade() | إعادة تعيين جميع السمات البصرية للواجهة الداخلية إلى قيمة فارغة. |
| rename_field(field_name, new_field_name) | تغيير اسم الحقل. |
| remove_field_action(field_name) | إزالة إجراء الإرسال للحقل. |
| add_submit_btn(field_name, page, label, url, llx, lly, urx, ury) | إضافة زر إرسال إلى النموذج. |
| del_list_item(field_name, item_name) | حذف عنصر من حقل القائمة. |
| set_field_script(field_name, script) | تعيين جافا سكريبت لحقل زر الضغط. إذا كان هناك جافا سكريبت قديم، سيتم استبداله بالجديد. |
| add_field_script(field_name, script) | إضافة جافا سكريبت لحقل زر الضغط. إذا كان هناك حدث قديم، يتم إضافة الحدث الجديد بعده. |
| single_2_multiple(field_name) | تحويل حقل نص أحادي السطر إلى حقل نص متعدد الأسطر. |
| set_field_alignment(field_name, alignment) | تعيين نمط محاذاة حقل النص. |
| set_field_alignment_v(field_name, alignment) | تعيين نمط المحاذاة العمودية لحقل النص. |

### انظر أيضًا

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

