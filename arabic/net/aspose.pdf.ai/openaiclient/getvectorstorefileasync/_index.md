---
title: OpenAIClient.GetVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تسترجع تفاصيل ملف معين داخل مخزن المتجهات بشكل غير متزامن
type: docs
weight: 340
url: /ar/net/aspose.pdf.ai/openaiclient/getvectorstorefileasync/
---
## طريقة OpenAIClient.GetVectorStoreFileAsync

تسترجع تفاصيل ملف معين داخل مخزن المتجهات بشكل غير متزامن.

```csharp
public Task<VectorStoreFileResponse> GetVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | سلسلة | معرف مخزن المتجهات الذي يحتوي على الملف. |
| fileId | سلسلة | معرف الملف الذي سيتم استرجاعه. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على تفاصيل الملف.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف مخزن المتجهات فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف الملف فارغًا أو null. |

### انظر أيضًا

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)