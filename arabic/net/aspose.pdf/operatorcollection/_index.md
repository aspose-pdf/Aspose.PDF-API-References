---
title: "الفئة OperatorCollection"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.OperatorCollection. تمثل الفئة مجموعة من المشغلات."
type: docs
weight: 7220
url: /ar/net/aspose.pdf/operatorcollection/
---
## OperatorCollection class

تمثل الفئة مجموعة من المشغلين.

```csharp
public class OperatorCollection : BaseOperatorCollection, IDisposable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count/) { get; } | يحصل على عدد المشغلات في المجموعة. |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode/) { get; } | يشير إلى ما إذا كانت المجموعة محدودة لاستخراج النص السريع. |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
| override [Item](../../aspose.pdf/operatorcollection/item/) { get; set; } | يحصل على المشغل حسب فهرسه. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept/)(IOperatorSelector) | يتقبل كائن الزائر IOperatorSelector لمعالجة المشغلات. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_2)(ICollection&lt;Operator&gt;) | يضيف إلى المجموعة جميع المشغلات من مجموعة أخرى. |
| override [Add](../../aspose.pdf/operatorcollection/add/#add)(Operator) | يضيف مشغلًا جديدًا إلى المجموعة. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_1)(Operator[]) | يضيف المشغلات في نهاية مشغلات المحتوى. |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate/)() | يلغي آخر تحديث. قد يتم استدعاء هذه الطريقة عندما لا يجب أن يؤدي التغيير إلى تحديث المحتوى. |
| override [Clear](../../aspose.pdf/operatorcollection/clear/)() | يزيل جميع المشغلات من القائمة. |
| override [Contains](../../aspose.pdf/operatorcollection/contains/)(Operator) | يرجع true إذا كانت المجموعة تحتوي على المشغل المحدد. |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto/)(Operator[], int) | ينسخ المشغلات إلى قائمة المشغلات. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_2)(IList&lt;Operator&gt;) | يحذف المشغلات من المجموعة. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_1)(int) | يحذف المشغل من المجموعة. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete)(Operator[]) | يحذف المشغلات من المجموعة. |
| [Dispose](../../aspose.pdf/operatorcollection/dispose/)() | ينفذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة تعيين الموارد غير المُدارة. |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator/)() | يعيد المُعدِّد للمجموعة |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_2)(int, IList&lt;Operator&gt;) | إدراج المشغّلات في الموضع المحدد. |
| override [Insert](../../aspose.pdf/operatorcollection/insert/#insert)(int, Operator) | يدرج المشغّل في المجموعة. |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_1)(int, Operator[]) | إدراج المشغّلات في الموضع المحدد. |
| override [Remove](../../aspose.pdf/operatorcollection/remove/)(Operator) | إزالة المشغّل من المجموعة. |
| [Replace](../../aspose.pdf/operatorcollection/replace/)(IList&lt;Operator&gt;) | استبدال المشغّلات في المجموعة بمشغّلات أخرى. |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate)() | يستأنف تحديث المستند. يُحدّث تدفق المحتوى في حال وجود أي تغييرات معلقة. |
| [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate_1)(bool) | يستأنف تحديث المستند. يُحدّث تدفق المحتوى في حال وجود أي تغييرات معلقة. يعلّم جميع المشغّلات بأنها \"متغيّرة\" إذا كان معامل invalidate صحيحًا. |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)() | يكبت تحديث بيانات المحتوى. لا يتم تحديث تدفق المحتوى حتى يتم استدعاء ResumeUpdate. |
| override [ToString](../../aspose.pdf/operatorcollection/tostring/)() | يعيد تمثيل النص للعامل. |

### انظر أيضًا

* class [BaseOperatorCollection](../baseoperatorcollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


