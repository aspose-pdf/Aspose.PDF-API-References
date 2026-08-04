---
title: "AutoFiller"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يمثل فئة لاستلام البيانات من قاعدة البيانات أو مصدر بيانات آخر، يملأها في الحقول المصممة في قالب PDF وأخيرًا يولد ملف PDF جديد أو تدفق.<br/>             لديها وضعا إدخال لملف القالب: إدخال كتيار أو كملف PDF.<br/>             لديها أربعة أنواع من أوضاع الإخراج: تيار مدمج واحد، ملف مدمج واحد، عدة تيارات صغيرة، عدة ملفات صغيرة.<br/>             يمكنه استلام البيانات الحرفية الموجودة في System.Data.DataTable."
type: docs
weight: 20
url: /ar/python-net/aspose.pdf.facades/autofiller/
---

## AutoFiller class

يمثل فئة لاستلام البيانات من قاعدة البيانات أو مصدر بيانات آخر، يملأها في الحقول المصممة في قالب PDF وأخيرًا يولد ملف PDF جديد أو تدفق.<br/>             لديها وضعا إدخال لملف القالب: إدخال كتيار أو كملف PDF.<br/>             لديها أربعة أنواع من أوضاع الإخراج: تيار مدمج واحد، ملف مدمج واحد، عدة تيارات صغيرة، عدة ملفات صغيرة.<br/>             يمكنه استلام البيانات الحرفية الموجودة في System.Data.DataTable.

يعرض نوع AutoFiller الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| AutoFiller() | يُنشئ نسخة جديدة من فئة AutoFiller |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| output_stream | يحصل أو يعيّن OutputStream. أحد أربعة أوضاع إخراج. الحالة الكلاسيكية لاستخدامه هي Response.OutputStream.<br/>            يرجى الرجوع إلى العرض التجريبي على الإنترنت. |
| output_streams | يحصل أو يعيّن العديد من Output Streams. أحد أربعة أوضاع إخراج. |
| input_stream | يحصل أو يعيّن تدفق قالب الإدخال. أحد وضعين للإدخال. |
| input_file_name | يحصل أو يعيّن ملف قالب الإدخال. أحد وضعين للإدخال. |
| output_file_name | يحصل أو يعيّن ملف الإخراج المدمج الكبير الواحد. أحد أربعة أوضاع إخراج. |
| generating_path | يحصل أو يعيّن مسار الإنشاء للملفات pdf الصغيرة إذا كان هناك العديد من ملفات pdf الصغيرة التي سيتم إنشاؤها. يعمل مع الخاصية الأخرى [basic_file_name](/pdf/python-net/aspose.pdf.facades/autofiller/)BasicFileName.<br/>            أحد أربعة أوضاع إخراج. |
| basic_file_name | يحصل أو يعيّن اسم الملف الأساسي إذا كان سيتم إنشاء العديد من الملفات الصغيرة. سيكون اسم الملف المُنشأ مثل \"BasicFileName0\",\"BasicFileName1\",...<br/>            يعمل مع الخاصية الأخرى [generating_path](/pdf/python-net/aspose.pdf.facades/autofiller/)GeneratingPath. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| save() | يحفظ جميع ملفات pdf. |
| save(dest_file) | يحفظ جميع ملفات pdf. |
| save(dest_stream) | يحفظ جميع ملفات pdf. |
| bind_pdf(src_file) | يربط ملف Pdf. |
| bind_pdf(src_stream) | يربط ملف Pdf. |
| bind_pdf(src_doc) | يربط مستند Pdf. |
| close() | يغلق الكائن وتدفقات الإخراج. |

### انظر أيضًا

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

