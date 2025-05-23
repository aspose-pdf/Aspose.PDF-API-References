---
title: IOpenAIClient.CreateVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تنشئ ملف تخزين متجه جديد بشكل غير متزامن
type: docs
weight: 110
url: /ar/net/aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/
---
## طريقة IOpenAIClient.CreateVectorStoreFileAsync

تنشئ ملف تخزين متجه جديد بشكل غير متزامن.

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | سلسلة | معرف تخزين المتجه حيث سيتم إنشاء الملف. |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | كائن الطلب الذي يحتوي على تفاصيل إنشاء الملف. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من إنشاء الملف.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف تخزين المتجه فارغًا أو غير موجود. |

### انظر أيضًا

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* class [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)