---
title: "Stamp"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "فئة تمثل الطابع."
type: docs
weight: 410
url: /ar/python-net/aspose.pdf.facades/stamp/
---

## Stamp class

فئة تمثل الطابع.

يعرض نوع Stamp الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| Stamp() | ينشئ مثيلاً جديداً لفئة Stamp |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| stamp_id | يحصل أو يعيّن معرف الطابع. |
| الجودة | يحصل أو يعيّن جودة طابع الصورة بالنسبة المئوية. القيم الممكنة 0..100%. |
| الشفافية | يحصل أو يعيّن شفافية الطابع. |
| page_number | يحصل أو يعيّن رقم الصفحة. |
| الصفحات | يحصل أو يعيّن مصفوفة بأرقام الصفحات التي سيتأثر بها الطابع. <br/>            إذا كانت Pages = null فإن جميع صفحات المستند سيتأثر بها. |
| rotation | يحصل أو يعيّن دوران الطابع بالدرجات. |
| is_background | يحصل أو يعيّن حالة الخلفية. إذا كان true سيُوضع الطابع كخلفية للصفحة المختومة.<br/>            بشكل افتراضي يتم تعيينه إلى false. |
| blending_space | يحصل أو يعيّن قيمة BlendingColorSpace التي تحدد مساحة لون <br/>            تُستخدم لإجراء عمليات الشفافية والدمج على الصفحة. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| bind_pdf(pdf_file, page_number) | يعيّن ملف PDF ورقم الصفحة التي ستُستخدم كطابع. |
| bind_pdf(pdf_stream, page_number) | يعيّن ملف PDF ورقم الصفحة التي ستُستخدم كطابع. |
| bind_image(image_file) | يعيّن الصورة كطابع. |
| bind_image(image) | يعيّن الصورة التي ستُستخدم كطابع. |
| bind_logo(formatted_text) | يعيّن النص كطابع. |
| bind_text_state(text_state) | يعيّن حالة نص الطابع. |
| set_origin(origin_x, origin_y) | يضبط الموضع على الصفحة حيث سيتم وضع الختم. |
| set_image_size(width, height) | يضبط حجم ختم الصورة. سيتم تحجيم الصورة وفق القيم المحددة. |

### انظر أيضًا

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

