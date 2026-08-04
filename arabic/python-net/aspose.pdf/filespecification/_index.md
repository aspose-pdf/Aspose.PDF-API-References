---
title: "FileSpecification"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "فئة تمثل ملفًا مضمّنًا."
type: docs
weight: 360
url: /ar/python-net/aspose.pdf/filespecification/
---

## FileSpecification class

فئة تمثل ملفًا مضمّنًا.

نوع FileSpecification يعرض الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| FileSpecification(file) | يقوم بتهيئة نسخة جديدة من الفئة FileSpecification |
| FileSpecification(stream, name) | يقوم بتهيئة نسخة جديدة من الفئة FileSpecification |
| FileSpecification(file, description) | يقوم بتهيئة نسخة جديدة من الفئة FileSpecification |
| FileSpecification(stream, name, description) | يقوم بتهيئة نسخة جديدة من الفئة FileSpecification |
| FileSpecification(file_name, annot) | يقوم بتهيئة نسخة جديدة من الفئة FileSpecification |
| FileSpecification() | إنشاء مواصفة ملف فارغة جديدة. |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| الترميز | يحصل أو يضبط تنسيق الترميز.<br/>            القيم الممكنة: Zip - يتم ضغط الملف باستخدام ZIP، <br/>            None - لا يتم ضغط الملف. |
| include_contents | إذا كان true، سيتم تضمين محتويات الملف في مواصفة الملف. |
| encrypted_payload | يحصل على الحمولة المشفرة. |
| الوصف | يحصل أو يعيّن النص المرتبط بمواصفات الملف. |
| af_relationship | العلاقة المرتبطة بالملف. |
| stream_contents | يحصل على محتويات الملف كدفق. <br/>            لا يتم تحميل المحتويات في الذاكرة مما يسمح بتقليل استهلاك الذاكرة.<br/>            لكن هذا الدفق لا يدعم التحديد ومخاصية Length. إذا كنت بحاجة إلى هذه الميزات يرجى استخدام خاصية Contents بدلاً من ذلك. |
| المحتويات | يحصل أو يعيّن محتوى الملف. <br/>            تُعيد هذه الخاصية البيانات المحمّلة في الذاكرة والتي قد تتسبب في استثناء نفاد الذاكرة للبيانات الكبيرة.<br/>            لتقليل استهلاك الذاكرة يرجى استخدام StreamContents. |
| params | يحصل على معلمات الملف. |
| mime_type | يحصل على النوع الفرعي للملف المضمن |
| name | يحصل أو يعيّن اسم مواصفات الملف. |
| unicode_name | يحصل أو يعيّن الاسم Unicode لمواصفات الملف. |
| file_system | يحصل أو يعيّن اسم نظام الملفات. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| get_value(key) | يحصل على معلمة خاصة بالتطبيق. |
| set_value(key, value) | يعيّن معلمة خاصة بالتطبيق. |

### انظر أيضًا

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

