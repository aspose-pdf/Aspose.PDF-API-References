---
title: "Form"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "فئة تمثل كائن نموذج Acro."
type: docs
weight: 80
url: /ar/python-net/aspose.pdf.facades/form/
---

## Form class

فئة تمثل كائن نموذج Acro.

نوع Form يكشف عن الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| Form(src_stream, dest_stream) | يُنشئ مثيلاً جديدًا من الفئة Form |
| Form() | منشئ Form بدون معلمات. |
| Form(src_file_name) | يُنشئ مثيلاً جديدًا من الفئة Form |
| Form(src_stream) | يُنشئ مثيلاً جديدًا من الفئة Form |
| Form(src_file_name, dest_file_name) | يُنشئ مثيلاً جديدًا من الفئة Form |
| Form(src_file_name, dest_stream) | يُنشئ مثيلاً جديدًا من الفئة Form |
| Form(src_stream, dest_file_name) | يُنشئ مثيلاً جديدًا من الفئة Form |
| Form(document) | يُنشئ مثيلاً جديدًا من الفئة Form |
| Form(document, dest_file_name) | يُنشئ مثيلاً جديدًا من الفئة Form |
| Form(document, dest_stream) | يُنشئ مثيلاً جديدًا من الفئة Form |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| مستند | يحصل على واجهة المستند التي يعمل عليها. |
| import_result | نتيجة عملية الاستيراد الأخيرة. مصفوفة من الكائنات التي تصف نتيجة الاستيراد لكل حقل. |
| src_file_name | يحصل أو يحدد اسم ملف المصدر. |
| dest_file_name | يحصل أو يحدد اسم ملف الوجهة. |
| src_stream | يحصل على أو يعيّن تدفق المصدر. |
| dest_stream | يحصل على أو يعيّن تدفق الوجهة. |
| field_names | يحصل على قائمة بأسماء الحقول في النموذج. |
| form_submit_button_names | يحصل على جميع أسماء أزرار إرسال النموذج. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| bind_pdf(src_file) | يربط مستند PDF للتحرير. |
| bind_pdf(src_stream) | يربط مستند PDF للتحرير. |
| bind_pdf(src_doc) | يربط مستند PDF للتحرير. |
| save() | يحفظ قيمة الحقول المملوءة ويغلق مستند PDF المفتوح. |
| save(dest_file) | يحفظ المستند في الملف المحدد. |
| save(dest_stream) | يحفظ المستند في الدفق المحدد. |
| fill_field(field_name, field_value) | يملأ الحقل بقيمة صالحة وفقًا لاسم الحقل المؤهل بالكامل.<br/> قبل ملء الحقول، يجب معرفة جميع أسماء الحقول والقيم الصالحة المقابلة لها.<br/> كل من اسم الحقل والقيم حساسة لحالة الأحرف.<br/> يرجى ملاحظة أن Aspose.Pdf.Facades يدعم فقط أسماء الحقول الكاملة ولا يعمل مع الأسماء الجزئية <br/> مقارنةً بـ Aspose.Pdf.Kit؛<br/> على سبيل المثال إذا كان للحقول اسم كامل "Form.Subform.TextField" يجب تحديد الاسم الكامل وليس "TextField". <br/> يمكنك استخدام خاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب باسمه الجزئي. |
| fill_field(field_name, index) | يملأ حقل صندوق الراديو بقيمة فهرس صالحة وفقًا لاسم الحقل المؤهل بالكامل.<br/> قبل ملء الحقول، يجب معرفة اسم الحقل فقط. بينما يمكن تحديد القيمة بواسطة فهرسها.<br/> ملاحظة: يُطبق فقط على حقول صندوق الراديو، وصندوق القائمة المنسدلة، وصناديق القائمة.<br/> يرجى ملاحظة أن Aspose.Pdf.Facades يدعم فقط أسماء الحقول الكاملة ولا يعمل مع الأسماء الجزئية <br/> مقارنةً بـ Aspose.Pdf.Kit؛<br/> على سبيل المثال إذا كان للحقول اسم كامل "Form.Subform.ListBoxField" يجب تحديد الاسم الكامل وليس "ListBoxField". <br/> يمكنك استخدام خاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب باسمه الجزئي. |
| fill_field(field_name, be_checked) | يملأ حقل خانة الاختيار بقيمة منطقية.<br/> ملاحظة: يُطبق فقط على خانة الاختيار.<br/> يرجى ملاحظة أن Aspose.Pdf.Facades يدعم فقط أسماء الحقول الكاملة ولا يعمل مع الأسماء الجزئية <br/> مقارنةً بـ Aspose.Pdf.Kit؛<br/> على سبيل المثال إذا كان للحقول اسم كامل "Form.Subform.CheckBoxField" يجب تحديد الاسم الكامل وليس "CheckBoxField". <br/> يمكنك استخدام خاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب باسمه الجزئي. |
| fill_field(field_name, field_values) | يملأ حقول صندوق النص بقيم نصية ويحفظ المستند.<br/> يتعلق بالمستندات الموقعة.<br/> ملاحظة: يُطبق فقط على صندوق النص.<br/> كل من اسم الحقل والقيم حساسة لحالة الأحرف. |
| fill_field(field_name, value, fit_font_size) | يملأ حقل خانة الاختيار بقيمة منطقية.<br/> ملاحظة: يُطبق فقط على خانة الاختيار.<br/> يرجى ملاحظة أن Aspose.Pdf.Facades يدعم فقط أسماء الحقول الكاملة ولا يعمل مع الأسماء الجزئية <br/> مقارنةً بـ Aspose.Pdf.Kit؛<br/> على سبيل المثال إذا كان للحقول اسم كامل "Form.Subform.CheckBoxField" يجب تحديد الاسم الكامل وليس "CheckBoxField". <br/> يمكنك استخدام خاصية FieldNames لاستكشاف أسماء الحقول الموجودة والبحث عن الحقل المطلوب باسمه الجزئي. |
| import_xml(input_xml_stream) | يستورد محتوى الحقول من ملف XML ويضعها في ملف PDF الجديد. |
| import_xml(input_xml_stream, ignore_form_template_changes) | يستورد محتوى الحقول من ملف XML ويضعها في ملف PDF الجديد. |
| fill_image_field(field_name, image_file_name) | يلصق صورة على حقل الزر الموجود كظهره وفقًا <br/> لاسم الحقل المؤهل بالكامل. |
| fill_image_field(field_name, image_stream) | وظيفة التحميل الزائد لـ FillImageField.<br/>            الإدخال هو تدفق صورة. |
| close() | يغلق الملفات المفتوحة دون أي تغييرات. |
| get_field_facade(field_name) | يعيد كائن FrofmFieldFacade الذي يحتوي على جميع سمات المظهر. |
| fill_fields(field_names, field_values, output) | يملأ حقول صندوق النص بقيم نصية ويحفظ المستند.<br/> يتعلق بالمستندات الموقعة.<br/> ملاحظة: يُطبق فقط على صندوق النص.<br/> كل من اسم الحقل والقيم حساسة لحالة الأحرف. |
| get_button_option_current_value(field_name) | يعيد القيمة الحالية لحقول خيارات زر الراديو. |
| get_field(field_name) | يعيد كائن FrofmFieldFacade الذي يحتوي على جميع سمات المظهر. |
| get_full_field_name(field_name) | يحصل على الاسم الكامل للحقل وفقًا لاسمه المختصر. |
| get_field_limit(field_name) | احصل على حد حقل النص. |
| flatten_all_fields() | يقوم بتسطيح جميع الحقول. |
| flatten_field(field_name) | يقوم بتسطيح حقل محدد باستخدام الاسم المؤهل بالكامل.<br/>            أي حقل آخر سيظل غير قابل للتغيير. إذا كان fieldName غير صالح، <br/>            جميع الحقول ستظل غير قابلة للتغيير. |
| fill_barcode_field(field_name, data) | املأ حقل الباركود وفقًا لاسمه المؤهل بالكامل. |
| import_fdf(input_fdf_stream) | يستورد محتوى الحقول من ملف fdf ويضعها في ملف pdf الجديد. |
| export_fdf(output_fdf_stream) | يصدّر محتوى حقول pdf إلى تدفق fdf. |
| export_xml(output_xml_stream) | يصدّر محتوى حقول pdf إلى تدفق xml.<br/>            قيمة حقل الزر لن يتم تصديرها. |
| extract_xfa_data(output_xml_stream) | يستخرج حزمة بيانات XFA |
| set_xfa_data(input_xml_stream) | يستبدل بيانات XFA بحزمة البيانات المحددة. يمكن استخراج حزمة البيانات باستخدام ExtractXfaData. |
| import_xfdf(input_xfdf_stream) | يستورد محتوى الحقول من ملف xfdf(xml) ويضعها في ملف pdf الجديد. |
| export_xfdf(output_xfdf_stream) | يصدّر محتوى حقول pdf إلى تدفق xml.<br/>            قيمة حقل الزر لن يتم تصديرها. |
| rename_field(field_name, new_field_name) | يعيد تسمية حقل. إما حقل AcroForm أو حقل XFA مقبول. |
| get_rich_text(field_name) | احصل على قيمة حقل Rich Text، بما في ذلك معلومات التنسيق لكل حرف. |
| get_submit_flags(field_name) | يعيد علامات الإرسال لزر الإرسال. |
| get_field_type(field_name) | يعيد نوع الحقل. |
| is_required_field(field_name) | يحدد ما إذا كان الحقل مطلوبًا أم لا. |
| get_field_flag(field_name) | يعيد علامات الحقل. |

### انظر أيضًا

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

