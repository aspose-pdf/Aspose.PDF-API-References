---
title: IOpenAIClient.WaitForVectorStoreToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تنتظر حتى يكتمل متجر المتجهات المحدد بشكل غير متزامن
type: docs
weight: 470
url: /ar/net/aspose.pdf.ai/iopenaiclient/waitforvectorstoretocompleteasync/
---
## طريقة IOpenAIClient.WaitForVectorStoreToCompleteAsync

تنتظر حتى يكتمل متجر المتجهات المحدد بشكل غير متزامن.

```csharp
public Task<VectorStoreResponse> WaitForVectorStoreToCompleteAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | سلسلة | معرف متجر المتجهات الذي سيتم مراقبته حتى الاكتمال. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الحالة النهائية لمتجر المتجهات.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف متجر المتجهات فارغًا أو غير موجود. |

### انظر أيضًا

* class [VectorStoreResponse](../../vectorstoreresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)