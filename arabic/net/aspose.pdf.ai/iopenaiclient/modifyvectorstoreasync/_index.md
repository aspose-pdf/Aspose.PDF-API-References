---
title: IOpenAIClient.ModifyVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تعدل مخزن المتجهات الموجود بشكل غير متزامن
type: docs
weight: 400
url: /ar/net/aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/
---
## طريقة IOpenAIClient.ModifyVectorStoreAsync

تعدل مخزن المتجهات الموجود بشكل غير متزامن.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | String | معرف مخزن المتجهات الذي سيتم تعديله. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | كائن الطلب الذي يحتوي على تفاصيل التعديل. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من تعديل مخزن المتجهات.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف مخزن المتجهات فارغًا أو null. |

### انظر أيضًا

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)