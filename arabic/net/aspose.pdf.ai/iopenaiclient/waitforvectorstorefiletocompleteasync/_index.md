---
title: IOpenAIClient.WaitForVectorStoreFileToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تنتظر حتى يكتمل ملف تخزين المتجهات المحدد بشكل غير متزامن
type: docs
weight: 460
url: /ar/net/aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync/
---
## طريقة IOpenAIClient.WaitForVectorStoreFileToCompleteAsync

تنتظر حتى يكتمل ملف تخزين المتجهات المحدد بشكل غير متزامن.

```csharp
public Task<VectorStoreFileResponse> WaitForVectorStoreFileToCompleteAsync(string vectorStoreId, 
    string fileId, CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | سلسلة | معرف تخزين المتجهات الذي يحتوي على الملف. |
| fileId | سلسلة | معرف الملف الذي سيتم مراقبته حتى الاكتمال. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الحالة النهائية للملف.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف تخزين المتجهات فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف الملف فارغًا أو null. |

### انظر أيضًا

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)