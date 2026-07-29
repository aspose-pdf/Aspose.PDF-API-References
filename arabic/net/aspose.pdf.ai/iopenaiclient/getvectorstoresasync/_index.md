---
title: "IOpenAIClient.GetVectorStoresAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة IOpenAIClient. تسترجع قائمة بمخازن المتجهات بشكل غير متزامن"
type: docs
weight: 350
url: /ar/net/aspose.pdf.ai/iopenaiclient/getvectorstoresasync/
---
## IOpenAIClient.GetVectorStoresAsync method

يسترجع قائمة بمخازن المتجهات بشكل غير متزامن.

```csharp
public Task<VectorStoreListResponse> GetVectorStoresAsync(
    VectorStoreListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| queryParameters | VectorStoreListQueryParameters | معلمات استعلام اختيارية لتصفية قائمة مخازن المتجهات. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. يحتوي نتيجة المهمة على قائمة بمخازن المتجهات.

### انظر أيضًا

* class [VectorStoreListResponse](../../vectorstorelistresponse/)
* class [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


