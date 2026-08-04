---
title: "PdfFileSanitization"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يمثل واجهة برمجة تطبيقات التنظيف والاستعادة.<br/>            استخدمها إذا لم تتمكن من إنشاء/فتح المستندات بأي طريقة أخرى."
type: docs
weight: 290
url: /ar/python-net/aspose.pdf.facades/pdffilesanitization/
---

## PdfFileSanitization class

يمثل واجهة برمجة تطبيقات التنظيف والاستعادة.<br/>            استخدمها إذا لم تتمكن من إنشاء/فتح المستندات بأي طريقة أخرى.

يعرض نوع PdfFileSanitization الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| PdfFileSanitization() | يُنشئ مثيلاً جديداً من الفئة PdfFileSanitization |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| مستند | يحصل على واجهة المستند التي يعمل عليها. |
| log | بعد أن تم حفظ الملف يمكنك التحقق مما تم القيام به مع الملف. |
| use_trim_top | يسمح بإزالة البيانات قبل بيانات PDF. |
| use_trim_bottom | يسمح بإزالة البيانات بعد بيانات PDF |
| use_rebuild_xref_and_trailer | يسمح بإنشاء xref و trailer جديدين للمستند. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| bind_pdf(input_file) | يربط ملف PDF للتنقية. |
| bind_pdf(input_stream) | يربط تدفق PDF للتنقية. |
| bind_pdf(src_doc) | يُهيئ الـ facade. |
| save(output_file) | يحفظ ملف PDF الناتج إلى ملف. |
| save(output_stream) | يحفظ ملف PDF الناتج إلى تدفق. |
| close() | يغلق الواجهة. |
| recover() | يستعيد المستند.<br/>            استخدم الخصائص للتخصيص. |
| trim_top() | يزيل البيانات قبل %PDF. |
| trim_bottom() | يزيل البيانات بعد آخر %%EOF. |
| rebuild_xref_and_trailer() | يزيل xref القديم مع التذييل ويُنشئ xref جديدًا مع التذييل. |

### انظر أيضًا

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

