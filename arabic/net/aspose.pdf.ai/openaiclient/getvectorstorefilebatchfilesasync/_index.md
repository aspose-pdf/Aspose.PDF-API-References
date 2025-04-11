---
title: OpenAIClient.GetVectorStoreFileBatchFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تسترجع قائمة بالملفات ضمن دفعة ملفات مخزن المتجهات المحددة بشكل غير متزامن
type: docs
weight: 360
url: /ar/net/aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/
---
## طريقة OpenAIClient.GetVectorStoreFileBatchFilesAsync

تسترجع قائمة بالملفات ضمن دفعة ملفات مخزن المتجهات المحددة بشكل غير متزامن.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | سلسلة | معرف مخزن المتجهات الذي يحتوي على دفعة الملفات. |
| fileBatchId | سلسلة | معرف دفعة الملفات لاسترجاع الملفات منها. |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | معلمات استعلام اختيارية لتصفية قائمة الملفات. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على قائمة بالملفات ضمن دفعة الملفات.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف مخزن المتجهات فارغًا أو غير موجود. |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف دفعة ملفات مخزن المتجهات فارغًا أو غير موجود. |

### انظر أيضًا

* class [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* class [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)