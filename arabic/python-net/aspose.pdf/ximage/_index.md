---
title: "XImage"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "الفئة تمثل كائن صورة X-Object."
type: docs
weight: 1680
url: /ar/python-net/aspose.pdf/ximage/
---

## XImage class

الفئة تمثل كائن صورة X-Object.

نوع XImage يعرض الأعضاء التالية:
## الخصائص
| الاسم | الوصف |
| :- | :- |
| contains_transparency | إذا كانت الصورة تحتوي على شفافية فترجع true؛ وإلا فترجع false. |
| grayscaled | يحصل على نسخة رمادية من الصورة. |
| filter_type | يحصل على نوع مرشح الصورة. |
| العرض | يحصل على عرض الصورة. |
| الارتفاع | يحصل على ارتفاع الصورة. |
| name | يحصل أو يعيّن اسم الصورة. يرجى ملاحظة أنه إذا قمت بتغيير اسم الصورة التي لديها مراجع في محتوى الصفحة، قد يصبح المستند غير صحيح. يرجى استخدام طريقة XImage.Rename في هذه الحالة. |
| metadata | بيانات تعريف الصورة. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| save(stream) | يحفظ بيانات الصورة في التدفق كصورة JPEG. |
| save(stream, format) | يحفظ الصورة في التدفق بالتنسيق المطلوب. |
| save(stream, resolution) | يحفظ بيانات الصورة في التدفق كصورة JPEG بدقة محددة. |
| save(stream, format, resolution) | يحفظ الصورة في التدفق بالتنسيق المطلوب بدقة محددة. |
| rename(name) | يعيد تسمية الصورة ويستبدل جميع المراجع إلى الصورة بالاسم الجديد |
| get_color_type() | يرجع نوع اللون للصورة. |
| detect_color_type(bmp) | يرجع نوع اللون للصورة. |
| is_the_same_object(image) | يرجع true إذا كانت الصورتان تشير إلى نفس الكائن. |
| get_name_in_collection() | يرجع اسم الصورة في مجموعة ints. |
| to_stream() | يرجع تدفق الصورة الأصلي. |

### انظر أيضًا

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

