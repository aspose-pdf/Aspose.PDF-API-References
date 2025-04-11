---
title: Class ThreadMessageListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.ThreadMessageListQueryParameters. كائن معلمات الاستعلام لقائمة رسائل الخيط
type: docs
weight: 1130
url: /ar/net/aspose.pdf.ai/threadmessagelistqueryparameters/
---
## ThreadMessageListQueryParameters class

كائن معلمات الاستعلام لقائمة رسائل الخيط.

```csharp
public class ThreadMessageListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Constructors

| Name | Description |
| --- | --- |
| [ThreadMessageListQueryParameters](threadmessagelistqueryparameters/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | يحصل أو يحدد مؤشرًا للاستخدام في الترقيم. after هو معرف كائن يحدد مكانك في القائمة. على سبيل المثال، إذا قمت بعمل طلب قائمة وتلقيت 100 كائن، ينتهي بـ obj_foo، يمكن أن يتضمن استدعائك التالي after=obj_foo من أجل جلب الصفحة التالية من القائمة. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | يحصل أو يحدد مؤشرًا للاستخدام في الترقيم. before هو معرف كائن يحدد مكانك في القائمة. على سبيل المثال، إذا قمت بعمل طلب قائمة وتلقيت 100 كائن، ينتهي بـ obj_foo، يمكن أن يتضمن استدعائك التالي before=obj_foo من أجل جلب الصفحة السابقة من القائمة. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | يحصل أو يحدد حدًا لعدد الكائنات التي سيتم إرجاعها. يمكن أن يتراوح الحد بين 1 و 100، والافتراضي هو 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | يحصل أو يحدد ترتيب الفرز حسب الطابع الزمني created_at للكائنات. asc للترتيب التصاعدي و desc للترتيب التنازلي. |
| [RunId](../../aspose.pdf.ai/threadmessagelistqueryparameters/runid/) { get; set; } | تصفية الرسائل حسب معرف التشغيل الذي أنشأها. |

## Methods

| Name | Description |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/threadmessagelistqueryparameters/getqueryparameters/)() | يحصل على معلمات الاستعلام لقائمة رسائل الخيط. |

### See Also

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)