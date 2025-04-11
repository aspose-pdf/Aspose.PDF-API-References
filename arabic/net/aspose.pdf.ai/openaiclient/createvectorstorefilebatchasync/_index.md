---
title: OpenAIClient.CreateVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تنشئ دفعة جديدة من ملفات تخزين المتجهات بشكل غير متزامن
type: docs
weight: 120
url: /ar/net/aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/
---
## طريقة OpenAIClient.CreateVectorStoreFileBatchAsync

تنشئ دفعة جديدة من ملفات تخزين المتجهات بشكل غير متزامن.

```csharp
public Task<VectorStoreFileBatchResponse> CreateVectorStoreFileBatchAsync(string vectorStoreId, 
    VectorStoreFileBatchCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | String | معرف تخزين المتجهات حيث سيتم إنشاء دفعة الملفات. |
| vectorStoreFileCreateRequest | VectorStoreFileBatchCreateRequest | كائن الطلب الذي يحتوي على تفاصيل إنشاء دفعة الملفات. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من إنشاء دفعة الملفات.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف تخزين المتجهات فارغًا أو غير موجود. |

### انظر أيضًا

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* class [VectorStoreFileBatchCreateRequest](../../vectorstorefilebatchcreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)