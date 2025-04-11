---
title: IOpenAIClient.GetVectorStoresAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تسترجع قائمة من متاجر المتجهات بشكل غير متزامن
type: docs
weight: 350
url: /ar/net/aspose.pdf.ai/iopenaiclient/getvectorstoresasync/
---
## طريقة IOpenAIClient.GetVectorStoresAsync

تسترجع قائمة من متاجر المتجهات بشكل غير متزامن.

```csharp
public Task<VectorStoreListResponse> GetVectorStoresAsync(
    VectorStoreListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| queryParameters | VectorStoreListQueryParameters | معاملات استعلام اختيارية لتصفية قائمة متاجر المتجهات. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على قائمة من متاجر المتجهات.

### انظر أيضًا

* class [VectorStoreListResponse](../../vectorstorelistresponse/)
* class [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)