---
title: "PdfXmpMetadata"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "فئة للتعامل مع بيانات XMP الوصفية."
type: docs
weight: 380
url: /ar/python-net/aspose.pdf.facades/pdfxmpmetadata/
---

## PdfXmpMetadata class

فئة للتعامل مع بيانات XMP الوصفية.

نوع PdfXmpMetadata يعرض الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| PdfXmpMetadata() | منشئ لـ PdfXmpMetadata. |
| PdfXmpMetadata(document) | يُنشئ مثيلًا جديدًا من الفئة PdfXmpMetadata |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| مستند | يحصل على واجهة المستند التي يعمل عليها. |
| المفاتيح | يحصل على المفاتيح من القاموس. |
| القيم | يحصل على مجموعة القيم في القاموس. |
| is_fixed_size | إرجاع true إذا كان التجميع ذو حجم ثابت. |
| is_synchronized | إرجاع true إذا كان التجميع متزامنًا. |
| sync_root | يحصل على كائن المزامنة للتجميع. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| bind_pdf(src_file) | يربط مستند PDF للتحرير. |
| bind_pdf(src_stream) | يربط مستند PDF للتحرير. |
| bind_pdf(src_doc) | يربط مستند PDF للتحرير. |
| save(dest_file) | يحفظ مستند PDF إلى الملف المحدد. |
| save(dest_stream) | يحفظ مستند PDF إلى الدفق المحدد. |
| add(key, value) | يضيف قيمة إلى بيانات XMP الوصفية. |
| add(xmp_pdf_a_extension_object, namespace_prefix, namespace_uri, schema_description) | يضيف حقل امتداد إلى البيانات الوصفية. |
| add(key, value) | يضيف عنصرًا جديدًا إلى كائن القاموس. |
| add(key, value) | يضيف حقل امتداد إلى البيانات الوصفية. |
| remove(key) | يزيل العنصر بالمفتاح المحدد. |
| remove(key) | يزيل المفتاح من القاموس. |
| contains(key) | يتحقق مما إذا كان القاموس يحتوي على المفتاح المحدد. |
| contains(property) | يتحقق مما إذا كان القاموس يحتوي على الخاصية المحددة. |
| get_xmp_metadata() | احصل على XmpMetadata لملف PDF المدخل بصيغة XML. |
| get_xmp_metadata(name) | احصل على جزء من XmpMetadata لملف pdf المدخل وفقًا لاسم ميتا. |
| close() | يطلق أي موارد مرتبطة بالواجهة الحالية. |
| register_namespace_uri(prefix, namespace_uri) | يسجل namespace URI. |
| get_namespace_uri_by_prefix(prefix) | يحصل على namespace URI حسب البادئة. |
| get_prefix_by_namespace_uri(namespace_uri) | يحصل على البادئة حسب namespace URI. |
| contains_key(key) | يحدد ما إذا كان هذا القاموس يحتوي على المفتاح المحدد. |
| try_get_value(key, value) | يحاول العثور على المفتاح في القاموس ويسترجع القيمة إذا تم العثور عليه. |

### انظر أيضًا

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

