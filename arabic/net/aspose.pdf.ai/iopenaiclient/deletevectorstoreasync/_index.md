---
title: IOpenAIClient.DeleteVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تحذف متجر المتجهات بشكل غير متزامن
type: docs
weight: 170
url: /ar/net/aspose.pdf.ai/iopenaiclient/deletevectorstoreasync/
---
## طريقة IOpenAIClient.DeleteVectorStoreAsync

تحذف متجر المتجهات بشكل غير متزامن.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | سلسلة | معرف متجر المتجهات المراد حذفه. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على حالة عملية الحذف.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم رميها عندما يكون معرف متجر المتجهات فارغًا أو null. |

### انظر أيضًا

* class [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)