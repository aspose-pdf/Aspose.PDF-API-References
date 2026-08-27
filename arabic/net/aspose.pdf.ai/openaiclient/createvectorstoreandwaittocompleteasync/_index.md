---
title: "OpenAIClient.CreateVectorStoreAndWaitToCompleteAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة OpenAIClient. تنشئ مخزنًا متجهًا جديدًا وتنتظر إكماله بشكل غير متزامن."
type: docs
weight: 90
url: /ar/net/aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/
---
## OpenAIClient.CreateVectorStoreAndWaitToCompleteAsync method

ينشئ مخزنًا متجهًا جديدًا وينتظر إكماله بشكل غير متزامن.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAndWaitToCompleteAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | كائن الطلب الذي يحتوي على تفاصيل إنشاء مخزن المتجهات. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. يحتوي نتيجة المهمة على الاستجابة من إنشاء مخزن المتجهات بعد الانتهاء.

### انظر أيضًا

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


