---
title: OpenAIClient.GetVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تسترجع تفاصيل مخزن المتجهات المحدد بشكل غير متزامن
type: docs
weight: 330
url: /ar/net/aspose.pdf.ai/openaiclient/getvectorstoreasync/
---
## طريقة OpenAIClient.GetVectorStoreAsync

تسترجع تفاصيل مخزن المتجهات المحدد بشكل غير متزامن.

```csharp
public Task<VectorStoreResponse> GetVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | String | معرف مخزن المتجهات الذي سيتم استرجاعه. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على تفاصيل مخزن المتجهات.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف مخزن المتجهات فارغًا أو غير موجود. |

### انظر أيضًا

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)