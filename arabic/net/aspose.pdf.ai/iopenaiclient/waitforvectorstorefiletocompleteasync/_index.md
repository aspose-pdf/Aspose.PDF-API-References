---
title: "IOpenAIClient.WaitForVectorStoreFileToCompleteAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة IOpenAIClient. تنتظر إكمال ملف مخزن المتجه المحدد بشكل غير متزامن"
type: docs
weight: 460
url: /ar/net/aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync/
---
## IOpenAIClient.WaitForVectorStoreFileToCompleteAsync method

ينتظر إكمال ملف مخزن متجه محدد بشكل غير متزامن.

```csharp
public Task<VectorStoreFileResponse> WaitForVectorStoreFileToCompleteAsync(string vectorStoreId, 
    string fileId, CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | String | معرّف مخزن المتجهات الذي يحتوي على الملف. |
| fileId | String | معرّف الملف الذي يتم مراقبته حتى الاكتمال. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. يحتوي نتيجة المهمة على الحالة النهائية للملف.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرّف مخزن المتجهات فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرف الملف فارغًا أو null. |

### انظر أيضًا

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


