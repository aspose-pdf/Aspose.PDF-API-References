---
title: OpenAIClient.GetVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تسترجع تفاصيل دفعة ملف مخزن المتجهات المحددة بشكل غير متزامن
type: docs
weight: 350
url: /ar/net/aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/
---
## طريقة OpenAIClient.GetVectorStoreFileBatchAsync

تسترجع تفاصيل دفعة ملف مخزن المتجهات المحددة بشكل غير متزامن.

```csharp
public Task<VectorStoreFileBatchResponse> GetVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | سلسلة | معرف مخزن المتجهات الذي يحتوي على دفعة الملف. |
| fileBatchId | سلسلة | معرف دفعة الملف التي سيتم استرجاعها. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على تفاصيل دفعة الملف.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف مخزن المتجهات فارغًا أو غير موجود. |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف دفعة ملف مخزن المتجهات فارغًا أو غير موجود. |

### انظر أيضًا

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)