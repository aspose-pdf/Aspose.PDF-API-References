---
title: "فئة VectorStoreFileListQueryParameters"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.AI.VectorStoreFileListQueryParameters. كائن معلمات الاستعلام لإدراج ملفات مخزن المتجهات"
type: docs
weight: 1420
url: /ar/net/aspose.pdf.ai/vectorstorefilelistqueryparameters/
---
## VectorStoreFileListQueryParameters class

كائن معلمات الاستعلام لسرد ملفات مخزن المتجهات.

```csharp
public class VectorStoreFileListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [VectorStoreFileListQueryParameters](vectorstorefilelistqueryparameters/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | يحصل أو يعيّن مؤشرًا للاستخدام في الترميز الصفحي. after هو معرف كائن يحدد موقعك في القائمة. على سبيل المثال، إذا قمت بطلب قائمة وتلقيت 100 كائن، ينتهي بـ obj_foo، يمكن للطلب اللاحق أن يتضمن after=obj_foo لجلب الصفحة التالية من القائمة. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | يحصل أو يعيّن مؤشرًا للاستخدام في الترميز الصفحي. before هو معرف كائن يحدد موقعك في القائمة. على سبيل المثال، إذا قمت بطلب قائمة وتلقيت 100 كائن، ينتهي بـ obj_foo، يمكن للطلب اللاحق أن يتضمن before=obj_foo لجلب الصفحة السابقة من القائمة. |
| [Filter](../../aspose.pdf.ai/vectorstorefilelistqueryparameters/filter/) { get; set; } | يحصل أو يعيّن مرشحًا حسب حالة الملف. أحد القيم: in_progress، completed، failed، cancelled. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | يحصل أو يعيّن حدًا لعدد الكائنات التي سيتم إرجاعها. يمكن أن يتراوح الحد بين 1 و 100، والافتراضي هو 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | يحصل أو يعيّن ترتيب الفرز حسب طابع الوقت created_at للكائنات. asc للترتيب التصاعدي و desc للترتيب التنازلي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorefilelistqueryparameters/getqueryparameters/)() | يحصل على معلمات الاستعلام لإدراج ملفات مخزن المتجهات. |

### انظر أيضًا

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


