---
title: "FormDataConverter"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يمثل فئة لتحويل البيانات من تنسيق إلى آخر.<br/>            يمكنه تحويل البيانات في fdf/xml/pdf/xfdf إلى OLEDB/OdbcDB.<br/>            يمكنه أيضًا تحويل البيانات في OLEDB/OdbcDB إلى البيانات في fdf/xml/xfdf.<br/>            يمكنه تحويل fdf إلى xml باستخدام وسم \"hard-named\"."
type: docs
weight: 100
url: /ar/python-net/aspose.pdf.facades/formdataconverter/
---

## FormDataConverter class

يمثل فئة لتحويل البيانات من تنسيق إلى آخر.<br/>            يمكنه تحويل البيانات في fdf/xml/pdf/xfdf إلى OLEDB/OdbcDB.<br/>            يمكنه أيضًا تحويل البيانات في OLEDB/OdbcDB إلى البيانات في fdf/xml/xfdf.<br/>            يمكنه تحويل fdf إلى xml باستخدام وسم "hard-named".

يعرض نوع FormDataConverter الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| FormDataConverter() | يُنشئ مثيلاً جديدًا من فئة FormDataConverter |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| create_missing_field | ستقوم ConvertToDataTable بإنشاء الحقل المطلوب إذا لم يكن موجودًا في الجدول. |
| replace_existing_table | ستقوم ImportIntoDatabase بحذف الجدول الموجود وإنشاء جدول جديد إذا تم تعيين هذه الخاصية إلى true. |
| clear_table_before_export | ستقوم ExportFromData بمسح الجدول قبل تصدير البيانات. |
| create_missing_table | ستقوم ImportIntoDatabase بإنشاء جدول إذا لم يكن موجودًا. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| convert_xml_to_fdf(source_xml, dest_fdf) | تحويل ملف بيانات نموذج استيراد/تصدير XML إلى تنسيق FDF. |
| convert_fdf_to_xml(source_fdf, dest_xml) | تحويل ملف FDF إلى XML. |
| convert_to_data_table(source_streams, source_type) | تحويل ملفات strems إلى جدول. |
| import_into_data_base(connect_string, db_type) | يستورد البيانات من الجدول إلى قاعدة البيانات. |
| export_from_data_base(connect_string, db_type) | يصدّر البيانات من قاعدة البيانات إلى الجدول. |
| convert_to_streams(dest_stream, dest_type) | تحويل البيانات في الجدول إلى تدفقات. |
| conver_to_streams(dest_stream, dest_type) | هذه الطريقة قديمة. يرجى استخدام ConvertToStreams() بدلاً من ذلك. |

### انظر أيضًا

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

