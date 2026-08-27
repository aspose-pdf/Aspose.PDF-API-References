---
title: "FontRepository"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يجري بحثًا عن الخطوط. يبحث في الخطوط المثبتة على النظام وخطوط PDF القياسية.<br/>             كما يوفر وظيفة لفتح الخطوط المخصصة."
type: docs
weight: 130
url: /ar/python-net/aspose.pdf.text/fontrepository/
---

## FontRepository class

يجري بحثًا عن الخطوط. يبحث في الخطوط المثبتة على النظام وخطوط PDF القياسية.<br/>             كما يوفر وظيفة لفتح الخطوط المخصصة.

نوع FontRepository يعرض الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| FontRepository() | ينشئ مثيلاً جديداً من الفئة FontRepository |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| substitutions | يحصل على مجموعة استراتيجيات استبدال الخطوط. |
| sources | يحصل على مجموعة مصادر الخطوط. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| find_font(font_name) | يبحث ويعيد الخط بالاسم المحدد. |
| find_font(font_name, ignore_case) | يبحث ويعيد الخط بالاسم المحدد مع تجاهل أو احترام حساسية الحالة. |
| find_font(font_family_name, stl) | يبحث ويعيد الخط بالاسم والنمط المحددين. |
| find_font(font_family_name, stl, ignore_case) | يبحث ويعيد الخط بالاسم والنمط المحددين <br/>             مع تجاهل أو احترام حساسية الحالة. |
| open_font(font_stream, font_type) | يفتح الخط باستخدام تدفق الخط المحدد. |
| open_font(font_file_path) | يفتح الخط باستخدام مسار ملف الخط المحدد. |
| open_font(font_file_path, metrics_file_path) | يفتح الخط باستخدام مسار ملف الخط المحدد. |
| load_fonts() | يقوم بتحميل الخطوط المثبتة على النظام وخطوط Pdf القياسية. تم تصميم هذه الطريقة لتسريع عملية تحميل الخطوط.<br/>            بشكل افتراضي يتم تحميل الخطوط عند أول طلب لأي خط. استخدام هذه الطريقة يحمل خطوط النظام والـ Pdf القياسية<br/>            فورًا قبل فتح أي مستند Pdf. |
| reload_fonts() | يعيد تحميل جميع الخطوط المحددة بواسطة الخاصية [sources](/pdf/python-net/aspose.pdf.text/fontrepository/) |

### انظر أيضًا

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

