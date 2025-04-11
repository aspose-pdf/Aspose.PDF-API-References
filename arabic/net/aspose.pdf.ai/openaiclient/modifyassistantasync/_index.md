---
title: OpenAIClient.ModifyAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تعدل مساعدًا موجودًا بشكل غير متزامن
type: docs
weight: 390
url: /ar/net/aspose.pdf.ai/openaiclient/modifyassistantasync/
---
## طريقة OpenAIClient.ModifyAssistantAsync

تعدل مساعدًا موجودًا بشكل غير متزامن.

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| assistantId | String | معرف المساعد الذي سيتم تعديله. |
| assistantModifyRequest | AssistantModifyRequest | كائن الطلب الذي يحتوي على تفاصيل التعديل. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من تعديل المساعد.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف المساعد فارغًا أو null. |

### انظر أيضًا

* class [AssistantResponse](../../assistantresponse/)
* class [AssistantModifyRequest](../../assistantmodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)