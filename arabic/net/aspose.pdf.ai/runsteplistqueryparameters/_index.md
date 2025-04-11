---
title: Class RunStepListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunStepListQueryParameters class. كائن معلمات الاستعلام لقائمة خطوات التشغيل
type: docs
weight: 1040
url: /ar/net/aspose.pdf.ai/runsteplistqueryparameters/
---
## RunStepListQueryParameters class

كائن معلمات الاستعلام لقائمة خطوات التشغيل.

```csharp
public class RunStepListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Constructors

| Name | Description |
| --- | --- |
| [RunStepListQueryParameters](runsteplistqueryparameters/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | يحصل أو يحدد مؤشرًا للاستخدام في الترقيم. after هو معرف كائن يحدد مكانك في القائمة. على سبيل المثال، إذا قمت بعمل طلب قائمة وتلقيت 100 كائن، ينتهي بـ obj_foo، يمكن أن يتضمن استدعاؤك التالي after=obj_foo من أجل جلب الصفحة التالية من القائمة. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | يحصل أو يحدد مؤشرًا للاستخدام في الترقيم. before هو معرف كائن يحدد مكانك في القائمة. على سبيل المثال، إذا قمت بعمل طلب قائمة وتلقيت 100 كائن، ينتهي بـ obj_foo، يمكن أن يتضمن استدعاؤك التالي before=obj_foo من أجل جلب الصفحة السابقة من القائمة. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | يحصل أو يحدد حدًا لعدد الكائنات التي سيتم إرجاعها. يمكن أن يتراوح الحد بين 1 و 100، والافتراضي هو 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | يحصل أو يحدد ترتيب الفرز حسب الطابع الزمني created_at للكائنات. asc للترتيب التصاعدي و desc للترتيب التنازلي. |

## Methods

| Name | Description |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/runsteplistqueryparameters/getqueryparameters/)() | يحصل على معلمات الاستعلام لقائمة خطوات التشغيل. |

### See Also

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)