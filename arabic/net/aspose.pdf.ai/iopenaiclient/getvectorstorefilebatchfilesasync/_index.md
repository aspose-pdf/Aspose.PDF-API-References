---
title: "IOpenAIClient.GetVectorStoreFileBatchFilesAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة IOpenAIClient. تسترجع قائمة بالملفات داخل دفعة ملفات مخزن المتجهات المحددة بشكل غير متزامن"
type: docs
weight: 330
url: /ar/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/
---
## IOpenAIClient.GetVectorStoreFileBatchFilesAsync method

يسترجع قائمة بالملفات داخل دفعة ملفات مخزن المتجه المحددة بشكل غير متزامن.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | String | معرّف مخزن المتجه الذي يحتوي على دفعة الملفات. |
| fileBatchId | String | معرّف مجموعة الملفات لاسترجاع الملفات منها. |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | معلمات استعلام اختيارية لتصفية قائمة الملفات. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. يحتوي نتيجة المهمة على قائمة بالملفات داخل مجموعة الملفات.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرّف مخزن المتجهات فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم إلقاؤها عندما يكون معرّف دفعة ملفات مخزن المتجه فارغًا أو null. |

### انظر أيضًا

* class [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* class [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


