---
title: "OperatorCollection"
second_title: "مرجع API لـ Aspose.PDF للبايثون عبر .NET"
description: "الفئة تمثل مجموعة من المشغّلات"
type: docs
weight: 1010
url: /ar/python-net/aspose.pdf/operatorcollection/
---

## OperatorCollection class

الفئة تمثل مجموعة من المشغّلات

يعرض نوع OperatorCollection الأعضاء التالية:
## الخصائص
| الاسم | الوصف |
| :- | :- |
| is_fast_text_extraction_mode | يشير إلى ما إذا كان التجميع محدودًا لاستخراج النص السريع |
## Indexer
| الاسم | الوصف |
| :- | :- |
| [index] | يحصل على المشغل حسب فهرسه. |
## الطرق
| الاسم | الوصف |
| :- | :- |
| insert(index, op) | يدرج المشغل في التجميع. |
| insert(at, ops) | إدراج المشغلات في الموضع المحدد. |
| insert(at, ops) | يدرج المشغل في التجميع. |
| delete(index) | يحذف المشغل من التجميع. |
| delete(ops) | يحذف المشغلات من التجميع. |
| delete(list) | لا شيء |
| add(ops) | إضافة المشغلات في نهاية مشغلات المحتوى. |
| add(ops) | يضيف مشغلًا جديدًا إلى التجميع. |
| suppress_update() | يقمع تحديث بيانات المحتوى.<br/>            لا يتم تحديث تدفق المحتوى حتى يتم استدعاء ResumeUpdate. |
| resume_update() | يستأنف تحديث المستند.<br/>            يحدث تدفق المحتوى في حال وجود أي تغييرات معلقة. |
| cancel_update() | يلغي آخر تحديث.<br/>            يمكن استدعاء هذه الطريقة عندما لا ينبغي للتغيير أن يسبب تحديث المحتوى. |
| accept(visitor) | يقبل كائن الزائر IOperatorSelector لمعالجة المشغلات. |
| replace(operators) | استبدل العوامل في المجموعة بعوامل أخرى. |

### انظر أيضًا

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

