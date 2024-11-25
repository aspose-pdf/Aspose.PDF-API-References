---
title: IOpenAIClient.WaitForAssistantMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Waits for the first message from the assistant within a thread asynchronously
type: docs
weight: 430
url: /net/aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/
---
## IOpenAIClient.WaitForAssistantMessageAsync method

Waits for the first message from the assistant within a thread asynchronously.

```csharp
public Task<ThreadMessageResponse> WaitForAssistantMessageAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread to monitor for the first assistant message. |
| queryParameters | ThreadMessageListQueryParameters | Optional query parameters to filter the list of messages. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the first assistant message in the thread.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


