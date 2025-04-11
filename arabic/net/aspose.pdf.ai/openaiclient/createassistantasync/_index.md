---
title: OpenAIClient.CreateAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تنشئ مساعدًا جديدًا بشكل غير متزامن
type: docs
weight: 30
url: /ar/net/aspose.pdf.ai/openaiclient/createassistantasync/
---
## طريقة OpenAIClient.CreateAssistantAsync

تنشئ مساعدًا جديدًا بشكل غير متزامن.

```csharp
public Task<AssistantResponse> CreateAssistantAsync(AssistantCreateRequest assistantCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| assistantCreateRequest | AssistantCreateRequest | كائن الطلب الذي يحتوي على تفاصيل إنشاء المساعد. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من إنشاء المساعد.

### انظر أيضًا

* class [AssistantResponse](../../assistantresponse/)
* class [AssistantCreateRequest](../../assistantcreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)