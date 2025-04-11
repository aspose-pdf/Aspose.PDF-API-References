---
title: IOpenAIClient.WaitForRunToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تنتظر حتى يكتمل التشغيل داخل خيط بشكل غير متزامن
type: docs
weight: 440
url: /ar/net/aspose.pdf.ai/iopenaiclient/waitforruntocompleteasync/
---
## IOpenAIClient.WaitForRunToCompleteAsync method

تنتظر حتى يكتمل التشغيل داخل خيط بشكل غير متزامن.

```csharp
public Task<RunResponse> WaitForRunToCompleteAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | معرف الخيط الذي يحتوي على التشغيل. |
| runId | String | معرف التشغيل الذي سيتم مراقبته حتى الاكتمال. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### Return Value

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الحالة النهائية للتشغيل.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحها عندما يكون معرف الخيط فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم طرحها عندما يكون معرف التشغيل فارغًا أو null. |

### See Also

* class [RunResponse](../../runresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)