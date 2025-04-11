---
title: IOpenAIClient.CreateVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تنشئ مخزن متجه جديد بشكل غير متزامن
type: docs
weight: 100
url: /ar/net/aspose.pdf.ai/iopenaiclient/createvectorstoreasync/
---
## طريقة IOpenAIClient.CreateVectorStoreAsync

تنشئ مخزن متجه جديد بشكل غير متزامن.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | كائن الطلب الذي يحتوي على تفاصيل إنشاء مخزن المتجه. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من إنشاء مخزن المتجه.

### انظر أيضًا

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)