---
title: "IOpenAIClient.GetVectorStoreFileBatchAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة IOpenAIClient. تسترجع تفاصيل دفعة ملفات مخزن متجه محدد بشكل غير متزامن"
type: docs
weight: 320
url: /ar/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/
---
## IOpenAIClient.GetVectorStoreFileBatchAsync method

يسترجع تفاصيل دفعة ملفات مخزن المتجه المحددة بشكل غير متزامن.

```csharp
public Task<VectorStoreFileBatchResponse> GetVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | String | معرّف مخزن المتجه الذي يحتوي على دفعة الملفات. |
| fileBatchId | String | معرّف دفعة الملفات المراد استرجاعها. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. يحتوي نتيجة المهمة على تفاصيل دفعة الملفات.

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


