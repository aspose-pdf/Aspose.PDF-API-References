---
title: IOpenAIClient.DeleteVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تحذف ملفًا داخل مخزن المتجهات بشكل غير متزامن
type: docs
weight: 180
url: /ar/net/aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync/
---
## طريقة IOpenAIClient.DeleteVectorStoreFileAsync

تحذف ملفًا داخل مخزن المتجهات بشكل غير متزامن.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | سلسلة | معرف مخزن المتجهات الذي يحتوي على الملف المراد حذفه. |
| fileId | سلسلة | معرف الملف المراد حذفه. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على حالة عملية الحذف.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف مخزن المتجهات فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف الملف فارغًا أو null. |

### انظر أيضًا

* class [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)