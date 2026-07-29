---
title: "IOpenAIClient.CreateThreadMessageAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة IOpenAIClient. تنشئ رسالة جديدة داخل خيط بشكل غير متزامن"
type: docs
weight: 80
url: /ar/net/aspose.pdf.ai/iopenaiclient/createthreadmessageasync/
---
## IOpenAIClient.CreateThreadMessageAsync method

ينشئ رسالة جديدة داخل خيط بشكل غير متزامن.

```csharp
public Task<ThreadMessageResponse> CreateThreadMessageAsync(string threadId, 
    ThreadMessageCreateRequest threadMessageRequest, CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرّف السلسلة التي ستُنشأ فيها الرسالة. |
| threadMessageRequest | ThreadMessageCreateRequest | تفاصيل الطلب لإنشاء الرسالة. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. يحتوي نتيجة المهمة على الاستجابة من إنشاء الرسالة.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرّف الخيط فارغًا أو null. |

### انظر أيضًا

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageCreateRequest](../../threadmessagecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


