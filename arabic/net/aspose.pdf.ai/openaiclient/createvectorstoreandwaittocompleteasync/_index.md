---
title: OpenAIClient.CreateVectorStoreAndWaitToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تنشئ متجر متجه جديد وتنتظر حتى يكتمل بشكل غير متزامن
type: docs
weight: 90
url: /ar/net/aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/
---
## طريقة OpenAIClient.CreateVectorStoreAndWaitToCompleteAsync

تنشئ متجر متجه جديد وتنتظر حتى يكتمل بشكل غير متزامن.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAndWaitToCompleteAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | كائن الطلب الذي يحتوي على تفاصيل إنشاء متجر المتجه. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من إنشاء متجر المتجه بعد الاكتمال.

### انظر أيضًا

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)