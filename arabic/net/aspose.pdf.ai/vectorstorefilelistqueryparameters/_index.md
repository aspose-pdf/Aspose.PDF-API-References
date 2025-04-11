---
title: Class VectorStoreFileListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.VectorStoreFileListQueryParameters. كائن معلمات الاستعلام لقائمة ملفات المتجر المتجه
type: docs
weight: 1330
url: /ar/net/aspose.pdf.ai/vectorstorefilelistqueryparameters/
---
## VectorStoreFileListQueryParameters class

كائن معلمات الاستعلام لقائمة ملفات المتجر المتجه.

```csharp
public class VectorStoreFileListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Constructors

| Name | Description |
| --- | --- |
| [VectorStoreFileListQueryParameters](vectorstorefilelistqueryparameters/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | يحصل أو يحدد مؤشرًا للاستخدام في الترقيم. after هو معرف كائن يحدد مكانك في القائمة. على سبيل المثال، إذا قمت بعمل طلب قائمة وتلقيت 100 كائن، ينتهي بـ obj_foo، يمكن أن تتضمن مكالمتك التالية after=obj_foo من أجل جلب الصفحة التالية من القائمة. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | يحصل أو يحدد مؤشرًا للاستخدام في الترقيم. before هو معرف كائن يحدد مكانك في القائمة. على سبيل المثال، إذا قمت بعمل طلب قائمة وتلقيت 100 كائن، ينتهي بـ obj_foo، يمكن أن تتضمن مكالمتك التالية before=obj_foo من أجل جلب الصفحة السابقة من القائمة. |
| [Filter](../../aspose.pdf.ai/vectorstorefilelistqueryparameters/filter/) { get; set; } | يحصل أو يحدد فلترًا حسب حالة الملف. واحد من in_progress، completed، failed، cancelled. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | يحصل أو يحدد حدًا لعدد الكائنات التي سيتم إرجاعها. يمكن أن يتراوح الحد بين 1 و 100، والافتراضي هو 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | يحصل أو يحدد ترتيب الفرز حسب الطابع الزمني created_at للكائنات. asc لترتيب تصاعدي و desc لترتيب تنازلي. |

## Methods

| Name | Description |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorefilelistqueryparameters/getqueryparameters/)() | يحصل على معلمات الاستعلام لقائمة ملفات المتجر المتجه. |

### See Also

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)