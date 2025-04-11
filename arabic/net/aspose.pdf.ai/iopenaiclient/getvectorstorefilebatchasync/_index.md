---
title: IOpenAIClient.GetVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تسترجع تفاصيل دفعة ملف مخزن المتجهات المحددة بشكل غير متزامن
type: docs
weight: 320
url: /ar/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/
---
## IOpenAIClient.GetVectorStoreFileBatchAsync method

تسترجع تفاصيل دفعة ملف مخزن المتجهات المحددة بشكل غير متزامن.

```csharp
public Task<VectorStoreFileBatchResponse> GetVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | معرف مخزن المتجهات الذي يحتوي على دفعة الملف. |
| fileBatchId | String | معرف دفعة الملف التي سيتم استرجاعها. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### Return Value

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على تفاصيل دفعة الملف.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحها عندما يكون معرف مخزن المتجهات فارغًا أو غير موجود. |
| [AIClientException](../../aiclientexception/) | يتم طرحها عندما يكون معرف دفعة ملف مخزن المتجهات فارغًا أو غير موجود. |

### See Also

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)