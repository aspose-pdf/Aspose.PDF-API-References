---
title: "XYZExplicitDestination"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "يمثل وجهة صريحة تعرض الصفحة مع إحداثيات (اليسار، الأعلى) موضوعة في الزاوية العلوية اليسرى للنافذة ومحتويات الصفحة مكبرة بمعامل التكبير. قيمة فارغة لأي من المعلمات اليسار أو الأعلى أو التكبير تعني أن القيمة الحالية لذلك المعامل تُحافظ عليها دون تغيير. قيمة التكبير 0 لها نفس معنى القيمة الفارغة."
type: docs
weight: 880
url: /ar/python-net/aspose.pdf.annotations/xyzexplicitdestination/
---

## XYZExplicitDestination class

يمثل وجهة صريحة تعرض الصفحة مع إحداثيات (اليسار، الأعلى) موضوعة في الزاوية العلوية اليسرى للنافذة ومحتويات الصفحة مكبرة بمعامل التكبير. قيمة فارغة لأي من المعلمات اليسار أو الأعلى أو التكبير تعني أن القيمة الحالية لذلك المعامل تُحافظ عليها دون تغيير. قيمة التكبير 0 لها نفس معنى القيمة الفارغة.

يعرض نوع XYZExplicitDestination الأعضاء التالية:
## المُنشئات
| الاسم | الوصف |
| :- | :- |
| XYZExplicitDestination(page, left, top, zoom) | ينشئ نسخة جديدة من فئة XYZExplicitDestination |
| XYZExplicitDestination(document, page_number, left, top, zoom) | ينشئ نسخة جديدة من فئة XYZExplicitDestination |
| XYZExplicitDestination(page_number, left, top, zoom) | ينشئ نسخة جديدة من فئة XYZExplicitDestination |
## الخصائص
| الاسم | الوصف |
| :- | :- |
| صفحة | يحصل على كائن صفحة الوجهة |
| page_number | يحصل على رقم صفحة الوجهة |
| left | يحصل على الإحداثي الأفقي الأيسر للزاوية العلوية اليسرى للنافذة. |
| top | يحصل على الإحداثي العمودي العلوي للزاوية العلوية اليسرى للنافذة. |
| zoom | يحصل على عامل التكبير. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| create_destination(page, left, top, zoom, consider_rotation) | إنشاء وجهة إلى الموقع المحدد للصفحة مع مراعاة دوران الصفحة إذا لزم الأمر. |
| create_destination(page, type, values) | ينشئ نسخًا من الفئات المشتقة من ExplicitDestination |
| create_destination(doc, page_number, type, values) | ينشئ نسخًا من الفئات المشتقة من ExplicitDestination |
| create_destination(page_number, type, values) | ينشئ نسخًا من الفئات المشتقة من ExplicitDestination |
| create_destination_to_upper_left_corner(page, zoom) | إنشاء وجهة إلى الزاوية العلوية اليسرى للصفحة المحددة. |
| create_destination_to_upper_left_corner(page) | إنشاء وجهة إلى الزاوية العلوية اليسرى للصفحة المحددة. |
| to_string() | يحوّل حالة الكائن إلى قيمة نصية. مثال: "1 XYZ 100 200 3". |

### انظر أيضًا

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

