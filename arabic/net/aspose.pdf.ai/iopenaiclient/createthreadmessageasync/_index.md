---
title: IOpenAIClient.CreateThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تنشئ رسالة جديدة داخل سلسلة بشكل غير متزامن
type: docs
weight: 80
url: /ar/net/aspose.pdf.ai/iopenaiclient/createthreadmessageasync/
---
## طريقة IOpenAIClient.CreateThreadMessageAsync

تنشئ رسالة جديدة داخل سلسلة بشكل غير متزامن.

```csharp
public Task<ThreadMessageResponse> CreateThreadMessageAsync(string threadId, 
    ThreadMessageCreateRequest threadMessageRequest, CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرف السلسلة التي سيتم إنشاء الرسالة فيها. |
| threadMessageRequest | ThreadMessageCreateRequest | تفاصيل الطلب لإنشاء الرسالة. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من إنشاء الرسالة.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم إلقاؤه عندما يكون معرف السلسلة فارغًا أو غير موجود. |

### انظر أيضًا

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageCreateRequest](../../threadmessagecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)