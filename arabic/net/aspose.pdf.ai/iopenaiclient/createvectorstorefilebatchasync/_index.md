---
title: "IOpenAIClient.CreateVectorStoreFileBatchAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة IOpenAIClient. تنشئ دفعة ملفات مخزن متجهات جديدة بشكل غير متزامن"
type: docs
weight: 120
url: /ar/net/aspose.pdf.ai/iopenaiclient/createvectorstorefilebatchasync/
---
## IOpenAIClient.CreateVectorStoreFileBatchAsync method

ينشئ دفعة ملفات مخزن متجه جديد بشكل غير متزامن.

```csharp
public Task<VectorStoreFileBatchResponse> CreateVectorStoreFileBatchAsync(string vectorStoreId, 
    VectorStoreFileBatchCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | String | معرّف مخزن المتجهات حيث سيتم إنشاء دفعة الملفات. |
| vectorStoreFileCreateRequest | VectorStoreFileBatchCreateRequest | كائن الطلب الذي يحتوي على تفاصيل إنشاء دفعة الملفات. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من إنشاء دفعة الملفات.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرّف مخزن المتجهات فارغًا أو null. |

### انظر أيضًا

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* class [VectorStoreFileBatchCreateRequest](../../vectorstorefilebatchcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


