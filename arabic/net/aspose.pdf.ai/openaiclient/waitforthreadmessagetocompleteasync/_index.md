---
title: OpenAIClient.WaitForThreadMessageToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تنتظر حتى تكتمل رسالة خيط معينة بشكل غير متزامن
type: docs
weight: 480
url: /ar/net/aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/
---
## طريقة OpenAIClient.WaitForThreadMessageToCompleteAsync

تنتظر حتى تكتمل رسالة خيط معينة بشكل غير متزامن.

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, 
    string threadMessageId, CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرف الخيط الذي يحتوي على الرسالة. |
| threadMessageId | String | معرف الرسالة التي سيتم مراقبتها حتى الاكتمال. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الحالة النهائية للرسالة.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف الخيط فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف رسالة الخيط فارغًا أو null. |

### انظر أيضًا

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)