---
title: Class VectorStoreFileBatchFileListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.VectorStoreFileBatchFileListQueryParameters. كائن معلمات الاستعلام لقائمة ملفات دفعة متجر المتجهات
type: docs
weight: 1290
url: /ar/net/aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/
---
## VectorStoreFileBatchFileListQueryParameters class

كائن معلمات الاستعلام لقائمة ملفات دفعة متجر المتجهات.

```csharp
public class VectorStoreFileBatchFileListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Constructors

| Name | Description |
| --- | --- |
| [VectorStoreFileBatchFileListQueryParameters](vectorstorefilebatchfilelistqueryparameters/)() | المُنشئ الافتراضي. |

## Properties

| Name | Description |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | يحصل أو يحدد مؤشرًا للاستخدام في الترقيم. after هو معرف كائن يحدد مكانك في القائمة. على سبيل المثال، إذا قمت بعمل طلب قائمة وتلقيت 100 كائن، ينتهي بـ obj_foo، يمكن أن يتضمن استدعائك التالي after=obj_foo من أجل جلب الصفحة التالية من القائمة. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | يحصل أو يحدد مؤشرًا للاستخدام في الترقيم. before هو معرف كائن يحدد مكانك في القائمة. على سبيل المثال، إذا قمت بعمل طلب قائمة وتلقيت 100 كائن، ينتهي بـ obj_foo، يمكن أن يتضمن استدعائك التالي before=obj_foo من أجل جلب الصفحة السابقة من القائمة. |
| [Filter](../../aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/filter/) { get; set; } | يحصل أو يحدد فلترًا حسب حالة الملف. واحد من in_progress، completed، failed، cancelled. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | يحصل أو يحدد حدًا لعدد الكائنات التي سيتم إرجاعها. يمكن أن يتراوح الحد بين 1 و 100، والافتراضي هو 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | يحصل أو يحدد ترتيب الفرز حسب الطابع الزمني created_at للكائنات. asc لترتيب تصاعدي و desc لترتيب تنازلي. |

## Methods

| Name | Description |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/getqueryparameters/)() | يحصل على معلمات الاستعلام لقائمة ملفات دفعة المتجر. |

### See Also

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)