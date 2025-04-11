---
title: OpenAIClient.DeleteAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تحذف مساعدًا موجودًا بشكل غير متزامن
type: docs
weight: 130
url: /ar/net/aspose.pdf.ai/openaiclient/deleteassistantasync/
---
## طريقة OpenAIClient.DeleteAssistantAsync

تحذف مساعدًا موجودًا بشكل غير متزامن.

```csharp
public Task<DeleteStatusResponse> DeleteAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| assistantId | String | معرف المساعد المراد حذفه. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على حالة عملية الحذف.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف المساعد فارغًا أو null. |

### انظر أيضًا

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)