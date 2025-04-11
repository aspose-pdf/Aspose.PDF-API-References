---
title: Class BaseOperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.BaseOperatorCollection. تمثل الفئة الأساسية لمجموعة المشغلين
type: docs
weight: 2830
url: /ar/net/aspose.pdf/baseoperatorcollection/
---
## فئة BaseOperatorCollection

تمثل الفئة الأساسية لمجموعة المشغلين.

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | يحصل على عدد المشغلين في المجموعة. |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | يشير إلى ما إذا كانت المجموعة محدودة لاستخراج النص السريع |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | يعيد true إذا كانت المجموعة للقراءة فقط. |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | يحصل على المشغل بواسطة فهرسه. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | يضيف مشغلًا جديدًا إلى المجموعة. |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | يلغي آخر تحديث. يمكن استدعاء هذه الطريقة عندما لا ينبغي أن يؤدي التغيير إلى تحديث المحتويات. |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | Clears collection. |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | يتحقق مما إذا كان المشغل موجودًا في المجموعة. |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | ينسخ المشغلين إلى قائمة المشغلين. |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | يعيد عدادًا للمجموعة |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | يُدخل مشغلًا في المجموعة. |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | يزيل المشغل من المجموعة. |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | يستأنف تحديث المستند. يقوم بتحديث تدفق المحتويات في حالة وجود أي تغييرات معلقة. |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | يمنع تحديث بيانات المحتويات. لا يتم تحديث تدفق المحتويات حتى يتم استدعاء ResumeUpdate. |

### انظر أيضًا

* class [Operator](../operator/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)