---
title: OpenAIClient.CancelVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تلغي دفعة ملفات مخزن المتجهات المحددة بشكل غير متزامن
type: docs
weight: 20
url: /ar/net/aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/
---
## طريقة OpenAIClient.CancelVectorStoreFileBatchAsync

تلغي دفعة ملفات مخزن المتجهات المحددة بشكل غير متزامن.

```csharp
public Task<VectorStoreFileBatchResponse> CancelVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | String | معرف مخزن المتجهات الذي يحتوي على دفعة الملفات المراد إلغاؤها. |
| fileBatchId | String | معرف دفعة الملفات المراد إلغاؤها. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من إلغاء دفعة الملفات.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف مخزن المتجهات فارغًا أو غير موجود. |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف دفعة ملفات مخزن المتجهات فارغًا أو غير موجود. |

### انظر أيضًا

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)