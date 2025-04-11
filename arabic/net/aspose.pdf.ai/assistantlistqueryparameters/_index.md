---
title: Class AssistantListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.AssistantListQueryParameters. تمثل كائن معلمات الاستعلام لقائمة المساعدين
type: docs
weight: 110
url: /ar/net/aspose.pdf.ai/assistantlistqueryparameters/
---
## فئة AssistantListQueryParameters

تمثل كائن معلمات الاستعلام لقائمة المساعدين.

```csharp
public class AssistantListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [AssistantListQueryParameters](assistantlistqueryparameters/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | يحصل أو يحدد مؤشرًا للاستخدام في الترقيم. after هو معرف كائن يحدد مكانك في القائمة. على سبيل المثال، إذا قمت بعمل طلب قائمة وتلقيت 100 كائن، ينتهي بـ obj_foo، يمكن أن تتضمن مكالمتك التالية after=obj_foo من أجل جلب الصفحة التالية من القائمة. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | يحصل أو يحدد مؤشرًا للاستخدام في الترقيم. before هو معرف كائن يحدد مكانك في القائمة. على سبيل المثال، إذا قمت بعمل طلب قائمة وتلقيت 100 كائن، ينتهي بـ obj_foo، يمكن أن تتضمن مكالمتك التالية before=obj_foo من أجل جلب الصفحة السابقة من القائمة. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | يحصل أو يحدد حدًا لعدد الكائنات التي سيتم إرجاعها. يمكن أن يتراوح الحد بين 1 و 100، والافتراضي هو 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | يحصل أو يحدد ترتيب الفرز حسب الطابع الزمني created_at للكائنات. asc للترتيب التصاعدي و desc للترتيب التنازلي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/assistantlistqueryparameters/getqueryparameters/)() | يحصل على معلمات الاستعلام لقائمة المساعدين. |

### انظر أيضًا

* فئة [BaseListQueryParameters](../baselistqueryparameters/)
* واجهة [IQueryParameters](../iqueryparameters/)
* مساحة الاسم [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* التجميع [Aspose.PDF](../../)