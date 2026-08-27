---
title: "الفئة VectorStoreListQueryParameters"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.AI.VectorStoreListQueryParameters. كائن معلمات الاستعلام لسرد مخازن المتجهات"
type: docs
weight: 1450
url: /ar/net/aspose.pdf.ai/vectorstorelistqueryparameters/
---
## VectorStoreListQueryParameters class

كائن معلمات الاستعلام لسرد مخازن المتجهات.

```csharp
public class VectorStoreListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [VectorStoreListQueryParameters](vectorstorelistqueryparameters/)() | البناء الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | يحصل أو يعيّن مؤشرًا للاستخدام في الترميز الصفحي. after هو معرف كائن يحدد موقعك في القائمة. على سبيل المثال، إذا قمت بطلب قائمة وتلقيت 100 كائن، ينتهي بـ obj_foo، يمكن للطلب اللاحق أن يتضمن after=obj_foo لجلب الصفحة التالية من القائمة. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | يحصل أو يعيّن مؤشرًا للاستخدام في الترميز الصفحي. before هو معرف كائن يحدد موقعك في القائمة. على سبيل المثال، إذا قمت بطلب قائمة وتلقيت 100 كائن، ينتهي بـ obj_foo، يمكن للطلب اللاحق أن يتضمن before=obj_foo لجلب الصفحة السابقة من القائمة. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | يحصل أو يعيّن حدًا لعدد الكائنات التي سيتم إرجاعها. يمكن أن يتراوح الحد بين 1 و 100، والافتراضي هو 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | يحصل أو يعيّن ترتيب الفرز حسب طابع الوقت created_at للكائنات. asc للترتيب التصاعدي و desc للترتيب التنازلي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorelistqueryparameters/getqueryparameters/)() | يحصل على معلمات الاستعلام لسرد مخازن المتجهات. |

### انظر أيضًا

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


