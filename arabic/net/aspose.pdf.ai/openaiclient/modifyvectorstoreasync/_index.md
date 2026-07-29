---
title: "OpenAIClient.ModifyVectorStoreAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة OpenAIClient. تعدّل مخزن متجهات موجود بشكل غير متزامن."
type: docs
weight: 440
url: /ar/net/aspose.pdf.ai/openaiclient/modifyvectorstoreasync/
---
## OpenAIClient.ModifyVectorStoreAsync method

يعدل مخزن متجه موجود بشكل غير متزامن.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | String | معرّف مخزن المتجهات المراد تعديله. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | كائن الطلب الذي يحتوي على تفاصيل التعديل. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من تعديل مخزن المتجهات.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرّف مخزن المتجهات فارغًا أو null. |

### انظر أيضًا

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


