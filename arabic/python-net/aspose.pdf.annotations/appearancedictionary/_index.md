---
title: "AppearanceDictionary"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "قاموس مظهر التعليق يحدد كيفية عرض التعليق بصريًا على الصفحة."
type: docs
weight: 60
url: /ar/python-net/aspose.pdf.annotations/appearancedictionary/
---

## AppearanceDictionary class

قاموس مظهر التعليق يحدد كيفية عرض التعليق بصريًا على الصفحة.

يعرض نوع AppearanceDictionary الأعضاء التالية:
## الخصائص
| الاسم | الوصف |
| :- | :- |
| is_fixed_size | يحصل على قيمة تشير إلى ما إذا كان القاموس ذو حجم ثابت. |
| keys | Gets keys of the dictionary. If appearance dictionary has subditionaries, then [keys](/pdf/python-net/aspose.pdf.annotations/appearancedictionary/) contains (N | R | قيم D).state,<br/>            حيث N - المظهر العادي، R - مظهر التمرير، D - مظهر الضغط وstate - اسم الحالة<br/>            (مثال: On, Off لمربعات الاختيار). |
| القيم | يحصل على قائمة قيم القاموس. <br/>            تحتوي مجموعة النتائج على قائمة كائنات XForm. |
| is_synchronized | يحصل على قيمة تشير إلى ما إذا كان الوصول إلى القاموس متزامنًا (آمن للخيوط). |
| sync_root | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى القاموس. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| add(key, value) | يضيف عنصرًا بالمفتاح والقيمة المقدمة. |
| add(key, value) | أضف نموذج X للمفتاح المحدد. |
| copy_to(array, index) | ينسخ عناصر القاموس إلى مصفوفة، بدءًا من فهرس مصفوفة معين. |
| contains_key(key) | يحدد ما إذا كان هذا القاموس يحتوي على المفتاح المحدد. |
| remove(key) | يزيل المفتاح من القاموس. |
| try_get_value(key, value) | يحاول العثور على المفتاح في القاموس ويسترجع القيمة إذا تم العثور عليه. |

### انظر أيضًا

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

