---
title: "IOpenAIClient.CancelVectorStoreFileBatchAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة IOpenAIClient. تلغي دفعة ملفات مخزن متجه محدد بشكل غير متزامن"
type: docs
weight: 20
url: /ar/net/aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/
---
## IOpenAIClient.CancelVectorStoreFileBatchAsync method

يلغي دفعة ملف مخزن المتجهات المحددة بشكل غير متزامن.

```csharp
public Task<VectorStoreFileBatchResponse> CancelVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | String | معرّف مخزن المتجهات الذي يحتوي على مجموعة الملفات المراد إلغاؤها. |
| fileBatchId | String | معرّف مجموعة الملفات المراد إلغاؤها. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من إلغاء مجموعة الملفات.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرّف مخزن المتجهات فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم إلقاؤها عندما يكون معرّف دفعة ملفات مخزن المتجه فارغًا أو null. |

### انظر أيضًا

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


