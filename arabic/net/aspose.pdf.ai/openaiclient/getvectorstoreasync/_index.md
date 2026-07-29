---
title: "OpenAIClient.GetVectorStoreAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة OpenAIClient. تسترجع تفاصيل مخزن متجه محدد بشكل غير متزامن"
type: docs
weight: 340
url: /ar/net/aspose.pdf.ai/openaiclient/getvectorstoreasync/
---
## OpenAIClient.GetVectorStoreAsync method

يسترجع تفاصيل مخزن متجه محدد بشكل غير متزامن.

```csharp
public Task<VectorStoreResponse> GetVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | String | معرّف مخزن المتجه لاسترجاعه. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. يحتوي نتيجة المهمة على تفاصيل مخزن المتجه.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرّف مخزن المتجهات فارغًا أو null. |

### انظر أيضًا

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


