---
title: Class OperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.OperatorCollection. تمثل الفئة مجموعة من المشغلين
type: docs
weight: 7080
url: /ar/net/aspose.pdf/operatorcollection/
---
## فئة مجموعة المشغلين

تمثل الفئة مجموعة من المشغلين

```csharp
public class OperatorCollection : BaseOperatorCollection, IDisposable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count/) { get; } | يحصل على عدد المشغلين في المجموعة. |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode/) { get; } | يشير إلى ما إذا كانت المجموعة محدودة بالاستخراج السريع للنص |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
| override [Item](../../aspose.pdf/operatorcollection/item/) { get; set; } | يحصل على المشغل بواسطة فهرسه. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept/)(IOperatorSelector) | يقبل كائن الزائر IOperatorSelector لمعالجة المشغلين. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_2)(ICollection&lt;Operator&gt;) | يضيف إلى المجموعة جميع المشغلين من مجموعة أخرى. |
| override [Add](../../aspose.pdf/operatorcollection/add/#add)(Operator) | يضيف مشغلًا جديدًا إلى المجموعة. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_1)(Operator[]) | يضيف المشغلين في نهاية محتويات المشغلين. |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate/)() | يلغي آخر تحديث. يمكن استدعاء هذه الطريقة عندما لا ينبغي أن يؤدي التغيير إلى تحديث المحتويات. |
| override [Clear](../../aspose.pdf/operatorcollection/clear/)() | يزيل جميع المشغلين من القائمة. |
| override [Contains](../../aspose.pdf/operatorcollection/contains/)(Operator) | يرجع true إذا كانت المجموعة تحتوي على المشغل المعطى. |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto/)(Operator[], int) | ينسخ المشغلين إلى قائمة المشغلين. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_2)(IList&lt;Operator&gt;) | يحذف المشغلين من المجموعة. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_1)(int) | يحذف مشغلًا من المجموعة. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete)(Operator[]) | يحذف المشغلين من المجموعة. |
| [Dispose](../../aspose.pdf/operatorcollection/dispose/)() | ينفذ المهام المحددة بواسطة التطبيق المرتبطة بتحرير أو إطلاق أو إعادة تعيين الموارد غير المُدارة. |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator/)() | يرجع عدادًا للمجموعة |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_2)(int, IList&lt;Operator&gt;) | يُدخل المشغلين في الموضع المحدد. |
| override [Insert](../../aspose.pdf/operatorcollection/insert/#insert)(int, Operator) | يُدخل مشغلًا في المجموعة. |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_1)(int, Operator[]) | يُدخل المشغلين في الموضع المحدد. |
| override [Remove](../../aspose.pdf/operatorcollection/remove/)(Operator) | يزيل مشغلًا من المجموعة. |
| [Replace](../../aspose.pdf/operatorcollection/replace/)(IList&lt;Operator&gt;) | يستبدل المشغلين في المجموعة بمشغلين آخرين. |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate)() | يستأنف تحديث الوثيقة. يحدث تدفق المحتويات في حالة وجود أي تغييرات معلقة. |
| [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate_1)(bool) | يستأنف تحديث الوثيقة. يحدث تدفق المحتويات في حالة وجود أي تغييرات معلقة. يحدد جميع المشغلين على أنهم "معدل" إذا كانت قيمة المعامل غير صالحة صحيحة. |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)() | يقمع تحديث بيانات المحتويات. لا يتم تحديث تدفق المحتويات حتى يتم استدعاء ResumeUpdate. |
| override [ToString](../../aspose.pdf/operatorcollection/tostring/)() | يرجع التمثيل النصي للمشغل. |

### انظر أيضًا

* فئة [BaseOperatorCollection](../baseoperatorcollection/)
* مساحة الأسماء [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)