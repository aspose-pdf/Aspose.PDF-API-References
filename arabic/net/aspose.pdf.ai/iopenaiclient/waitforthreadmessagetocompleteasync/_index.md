---
title: IOpenAIClient.WaitForThreadMessageToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تنتظر حتى تكتمل رسالة خيط معينة بشكل غير متزامن
type: docs
weight: 450
url: /ar/net/aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/
---
## IOpenAIClient.WaitForThreadMessageToCompleteAsync method

تنتظر حتى تكتمل رسالة خيط معينة بشكل غير متزامن.

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, 
    string threadMessageId, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | معرف الخيط الذي يحتوي على الرسالة. |
| threadMessageId | String | معرف الرسالة التي سيتم مراقبتها حتى الاكتمال. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### Return Value

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الحالة النهائية للرسالة.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحها عندما يكون معرف الخيط فارغًا أو غير موجود. |
| [AIClientException](../../aiclientexception/) | يتم طرحها عندما يكون معرف رسالة الخيط فارغًا أو غير موجود. |

### See Also

* class [ThreadMessageResponse](../../threadmessageresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)