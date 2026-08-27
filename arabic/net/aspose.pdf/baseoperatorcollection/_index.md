---
title: "الفئة BaseOperatorCollection"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.BaseOperatorCollection. تمثل الفئة الأساسية لمجموعة المشغلات."
type: docs
weight: 2940
url: /ar/net/aspose.pdf/baseoperatorcollection/
---
## BaseOperatorCollection class

تمثل الفئة الأساسية لمجموعة المشغلات.

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | يحصل على عدد المشغلات في المجموعة. |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | يشير إلى ما إذا كانت المجموعة محدودة لاستخراج النص السريع. |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | يرجع true إذا كانت المجموعة للقراءة فقط. |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | يحصل على المشغل حسب فهرسه. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | يضيف مشغلًا جديدًا إلى المجموعة. |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | يلغي آخر تحديث. قد يتم استدعاء هذه الطريقة عندما لا يجب أن يؤدي التغيير إلى تحديث المحتوى. |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | يمسح المجموعة. |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | يتحقق مما إذا كان المشغل موجودًا في المجموعة. |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | ينسخ المشغلات إلى قائمة المشغلات. |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | يعيد المُعدِّد للمجموعة |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | يدرج المشغّل في المجموعة. |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | يزيل المشغل من المجموعة. |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | يستأنف تحديث المستند. يُحدّث تدفق المحتوى في حال وجود أي تغييرات معلقة. |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | يكبت تحديث بيانات المحتوى. لا يتم تحديث تدفق المحتوى حتى يتم استدعاء ResumeUpdate. |

### انظر أيضًا

* class [Operator](../operator/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


