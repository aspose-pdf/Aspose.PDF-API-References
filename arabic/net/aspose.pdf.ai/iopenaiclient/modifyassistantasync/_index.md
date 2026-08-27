---
title: "IOpenAIClient.ModifyAssistantAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة IOpenAIClient. تُعدّل مساعدًا موجودًا بشكل غير متزامن"
type: docs
weight: 360
url: /ar/net/aspose.pdf.ai/iopenaiclient/modifyassistantasync/
---
## IOpenAIClient.ModifyAssistantAsync method

يعدل مساعدًا موجودًا بشكل غير متزامن.

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| assistantId | String | معرف المساعد الذي سيتم تعديله. |
| assistantModifyRequest | AssistantModifyRequest | كائن الطلب الذي يحتوي على تفاصيل التعديل. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. يحتوي نتيجة المهمة على الاستجابة من تعديل المساعد.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرف المساعد null أو فارغ. |

### انظر أيضًا

* class [AssistantResponse](../../assistantresponse/)
* class [AssistantModifyRequest](../../assistantmodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


