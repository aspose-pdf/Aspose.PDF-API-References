---
title: "PdfAnnotationEditor"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يمثل فئة للعمل مع تعليقات مستند PDF (التعليقات)."
type: docs
weight: 170
url: /ar/python-net/aspose.pdf.facades/pdfannotationeditor/
---

## PdfAnnotationEditor class

يمثل فئة للعمل مع تعليقات مستند PDF (التعليقات).

نوع PdfAnnotationEditor يعرض الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| PdfAnnotationEditor() | ينشئ كائنًا جديدًا من [PdfAnnotationEditor](/pdf/python-net/aspose.pdf.facades/pdfannotationeditor/). |
| PdfAnnotationEditor(document) | ينشئ نسخة جديدة من فئة PdfAnnotationEditor |
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
| import_annotations_from_xfdf(xfdf_file) | يستورد جميع التعليقات التوضيحية من ملف XFDF. |
| import_annotations_from_xfdf(xfdf_stream) | يستورد جميع التعليقات التوضيحية من تدفق بيانات XFDF. |
| import_annotation_from_xfdf(xfdf_file) | يستورد جميع التعليقات التوضيحية من ملف XFDF. |
| import_annotation_from_xfdf(xfdf_file, annot_type) | يستورد التعليقات التوضيحية المحددة من ملف XFDF. |
| import_annotation_from_xfdf(xfdf_stream, annot_type) | يستورد التعليقات التوضيحية المحددة من تدفق بيانات XFDF. |
| import_annotation_from_xfdf(xfdf_stream) | يستورد التعليقات التوضيحية المحددة من تدفق بيانات XFDF. |
| import_annotations(annot_file, annot_type) | يستورد التعليقات التوضيحية المحددة إلى المستند من مجموعة من مستندات PDF أخرى. |
| import_annotations(annot_file) | يستورد التعليقات التوضيحية المحددة إلى المستند من مجموعة من مستندات PDF أخرى. |
| import_annotations(annot_file_stream, annot_type) | يستورد التعليقات التوضيحية المحددة إلى المستند من مصفوفة تدفقات مستند PDF آخر. |
| import_annotations(annot_file_stream) | يستورد التعليقات التوضيحية المحددة إلى المستند من مصفوفة تدفقات مستند PDF آخر. |
| flattening_annotations() | يطوي جميع التعليقات التوضيحية في المستند. |
| flattening_annotations(flatten_settings) | يطوي جميع التعليقات التوضيحية في المستند. |
| flattening_annotations(start, end, annot_type) | يطوي التعليقات التوضيحية للأنواع المحددة. |
| delete_annotations() | يحذف جميع التعليقات التوضيحية في المستند. |
| delete_annotations(annot_type) | يحذف جميع التعليقات التوضيحية من النوع المحدد في المستند. |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | يصدّر محتوى أنواع التعليقات التوضيحية المحددة إلى XFDF |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | يصدّر محتوى أنواع التعليقات التوضيحية المحددة إلى XFDF |
| extract_annotations(start, end, annot_types) | يحصل على قائمة التعليقات التوضيحية للأنواع المحددة. |
| extract_annotations(start, end, annot_types) | يحصل على قائمة التعليقات التوضيحية للأنواع المحددة. |
| close() | يطلق أي موارد مرتبطة بالواجهة الحالية. |
| modify_annotations_author(start, end, src_author, des_author) | يعدّل مؤلف التعليقات التوضيحية في نطاق الصفحات المحدد. |
| delete_annotation(annot_name) | يحذف جميع التعليقات التوضيحية من النوع المحدد في المستند. |
| export_annotations_to_xfdf(xml_output_stream) | يصدّر التعليقات التوضيحية إلى التدفق. |
| modify_annotations(start, end, annotation) | يعدّل التعليقات التوضيحية من النوع المحدد في نطاق الصفحات المحدد.<br/>            يدعم تعديل الخصائص التالية للتعليقات التوضيحية: Modified, Title, Contents, Color, Subject و Open. |
| redact_area(page_index, rect, color) | يقوم بتغطية المنطقة في الصفحة المحددة. جميع المحتويات تُزال. |

### انظر أيضًا

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

