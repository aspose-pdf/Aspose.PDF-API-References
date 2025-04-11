---
title: IOpenAIClient.DeleteFileAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تحذف ملفًا معينًا بشكل غير متزامن
type: docs
weight: 140
url: /ar/net/aspose.pdf.ai/iopenaiclient/deletefileasync/
---
## طريقة IOpenAIClient.DeleteFileAsync

تحذف ملفًا معينًا بشكل غير متزامن.

```csharp
public Task<DeleteStatusResponse> DeleteFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fileId | String | معرف الملف المراد حذفه. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على حالة عملية الحذف.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف الملف فارغًا أو null. |

### انظر أيضًا

* class [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)