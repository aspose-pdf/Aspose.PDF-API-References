---
title: IOpenAIClient.GetVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تسترجع تفاصيل ملف معين داخل مخزن المتجهات بشكل غير متزامن
type: docs
weight: 310
url: /ar/net/aspose.pdf.ai/iopenaiclient/getvectorstorefileasync/
---
## IOpenAIClient.GetVectorStoreFileAsync method

تسترجع تفاصيل ملف معين داخل مخزن المتجهات بشكل غير متزامن.

```csharp
public Task<VectorStoreFileResponse> GetVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | معرف مخزن المتجهات الذي يحتوي على الملف. |
| fileId | String | معرف الملف الذي سيتم استرجاعه. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### Return Value

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على تفاصيل الملف.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحها عندما يكون معرف مخزن المتجهات فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم طرحها عندما يكون معرف الملف فارغًا أو null. |

### See Also

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)