---
title: IOpenAIClient.CreateVectorStoreAndWaitToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تنشئ مخزن متجه جديد وتنتظر حتى يكتمل بشكل غير متزامن
type: docs
weight: 90
url: /ar/net/aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync/
---
## IOpenAIClient.CreateVectorStoreAndWaitToCompleteAsync method

تنشئ مخزن متجه جديد وتنتظر حتى يكتمل بشكل غير متزامن.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAndWaitToCompleteAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | كائن الطلب الذي يحتوي على تفاصيل إنشاء مخزن المتجه. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### Return Value

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من إنشاء مخزن المتجه بعد الاكتمال.

### See Also

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)