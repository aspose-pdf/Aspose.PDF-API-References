---
title: OpenAIClient.GetVectorStoreFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تسترجع قائمة بالملفات داخل متجر متجه محدد بشكل غير متزامن
type: docs
weight: 370
url: /ar/net/aspose.pdf.ai/openaiclient/getvectorstorefilesasync/
---
## طريقة OpenAIClient.GetVectorStoreFilesAsync

تسترجع قائمة بالملفات داخل متجر متجه محدد بشكل غير متزامن.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFilesAsync(string vectorStoreId, 
    VectorStoreFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | سلسلة | معرف متجر المتجه الذي يحتوي على الملفات. |
| queryParameters | VectorStoreFileListQueryParameters | معلمات استعلام اختيارية لتصفية قائمة الملفات. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على قائمة بالملفات داخل متجر المتجه.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف متجر المتجه فارغًا أو null. |

### انظر أيضًا

* class [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* class [VectorStoreFileListQueryParameters](../../vectorstorefilelistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)