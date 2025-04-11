---
title: IOpenAIClient.CancelVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تلغي دفعة ملفات مخزن المتجهات المحددة بشكل غير متزامن
type: docs
weight: 20
url: /ar/net/aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/
---
## IOpenAIClient.CancelVectorStoreFileBatchAsync method

تلغي دفعة ملفات مخزن المتجهات المحددة بشكل غير متزامن.

```csharp
public Task<VectorStoreFileBatchResponse> CancelVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | معرف مخزن المتجهات الذي يحتوي على دفعة الملفات المراد إلغاؤها. |
| fileBatchId | String | معرف دفعة الملفات المراد إلغاؤها. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### Return Value

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من إلغاء دفعة الملفات.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحها عندما يكون معرف مخزن المتجهات فارغًا أو غير موجود. |
| [AIClientException](../../aiclientexception/) | يتم طرحها عندما يكون معرف دفعة ملفات مخزن المتجهات فارغًا أو غير موجود. |

### See Also

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)