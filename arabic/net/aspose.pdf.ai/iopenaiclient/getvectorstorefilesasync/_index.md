---
title: IOpenAIClient.GetVectorStoreFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تسترجع قائمة بالملفات داخل متجر متجه محدد بشكل غير متزامن
type: docs
weight: 340
url: /ar/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/
---
## IOpenAIClient.GetVectorStoreFilesAsync method

تسترجع قائمة بالملفات داخل متجر متجه محدد بشكل غير متزامن.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFilesAsync(string vectorStoreId, 
    VectorStoreFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | معرف متجر المتجه الذي يحتوي على الملفات. |
| queryParameters | VectorStoreFileListQueryParameters | معلمات استعلام اختيارية لتصفية قائمة الملفات. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### Return Value

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على قائمة بالملفات داخل متجر المتجه.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحها عندما يكون معرف متجر المتجه فارغًا أو غير موجود. |

### See Also

* class [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* class [VectorStoreFileListQueryParameters](../../vectorstorefilelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)