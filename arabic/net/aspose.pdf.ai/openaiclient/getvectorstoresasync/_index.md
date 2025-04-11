---
title: OpenAIClient.GetVectorStoresAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تسترجع قائمة من متاجر المتجهات بشكل غير متزامن
type: docs
weight: 380
url: /ar/net/aspose.pdf.ai/openaiclient/getvectorstoresasync/
---
## طريقة OpenAIClient.GetVectorStoresAsync

تسترجع قائمة من متاجر المتجهات بشكل غير متزامن.

```csharp
public Task<VectorStoreListResponse> GetVectorStoresAsync(
    VectorStoreListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| queryParameters | VectorStoreListQueryParameters | معلمات استعلام اختيارية لتصفية قائمة متاجر المتجهات. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على قائمة من متاجر المتجهات.

### انظر أيضًا

* class [VectorStoreListResponse](../../vectorstorelistresponse/)
* class [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)