---
title: OpenAIClient.CreateVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تنشئ ملف تخزين متجه جديد بشكل غير متزامن
type: docs
weight: 110
url: /ar/net/aspose.pdf.ai/openaiclient/createvectorstorefileasync/
---
## طريقة OpenAIClient.CreateVectorStoreFileAsync

تنشئ ملف تخزين متجه جديد بشكل غير متزامن.

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | String | معرف تخزين المتجه حيث سيتم إنشاء الملف. |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | كائن الطلب الذي يحتوي على تفاصيل إنشاء الملف. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من إنشاء الملف.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف تخزين المتجه فارغًا أو null. |

### انظر أيضًا

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* class [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)