---
title: IOpenAIClient.WaitForThreadMessageToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Waits for a specific thread message to complete asynchronously
type: docs
weight: 450
url: /net/aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/
---
## IOpenAIClient.WaitForThreadMessageToCompleteAsync method

Waits for a specific thread message to complete asynchronously.

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, 
    string threadMessageId, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread containing the message. |
| threadMessageId | String | The ID of the message to monitor until completion. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the final status of the message.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the thread message Id is null or empty. |

### See Also

* class [ThreadMessageResponse](../../threadmessageresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


