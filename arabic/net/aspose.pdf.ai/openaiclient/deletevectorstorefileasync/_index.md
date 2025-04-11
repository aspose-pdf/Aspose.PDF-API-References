---
title: OpenAIClient.DeleteVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تحذف ملفًا داخل مخزن متجه بشكل غير متزامن
type: docs
weight: 180
url: /ar/net/aspose.pdf.ai/openaiclient/deletevectorstorefileasync/
---
## طريقة OpenAIClient.DeleteVectorStoreFileAsync

تحذف ملفًا داخل مخزن متجه بشكل غير متزامن.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | سلسلة | معرف مخزن المتجه الذي يحتوي على الملف المراد حذفه. |
| fileId | سلسلة | معرف الملف المراد حذفه. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على حالة عملية الحذف.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف مخزن المتجه فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف الملف فارغًا أو null. |

### انظر أيضًا

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)