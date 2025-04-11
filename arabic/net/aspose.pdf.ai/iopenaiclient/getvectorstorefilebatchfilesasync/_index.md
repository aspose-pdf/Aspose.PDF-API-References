---
title: IOpenAIClient.GetVectorStoreFileBatchFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تسترجع قائمة بالملفات ضمن دفعة ملفات مخزن المتجهات المحدد بشكل غير متزامن
type: docs
weight: 330
url: /ar/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/
---
## IOpenAIClient.GetVectorStoreFileBatchFilesAsync method

تسترجع قائمة بالملفات ضمن دفعة ملفات مخزن المتجهات المحدد بشكل غير متزامن.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | معرف مخزن المتجهات الذي يحتوي على دفعة الملفات. |
| fileBatchId | String | معرف دفعة الملفات لاسترجاع الملفات منها. |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | معلمات استعلام اختيارية لتصفية قائمة الملفات. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### Return Value

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على قائمة بالملفات ضمن دفعة الملفات.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحها عندما يكون معرف مخزن المتجهات فارغًا أو غير موجود. |
| [AIClientException](../../aiclientexception/) | يتم طرحها عندما يكون معرف دفعة ملفات مخزن المتجهات فارغًا أو غير موجود. |

### See Also

* class [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* class [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)