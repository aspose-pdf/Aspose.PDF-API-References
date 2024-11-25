---
title: IOpenAIClient.CreateThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Creates a new message within a thread asynchronously
type: docs
weight: 80
url: /net/aspose.pdf.ai/iopenaiclient/createthreadmessageasync/
---
## IOpenAIClient.CreateThreadMessageAsync method

Creates a new message within a thread asynchronously.

```csharp
public Task<ThreadMessageResponse> CreateThreadMessageAsync(string threadId, 
    ThreadMessageCreateRequest threadMessageRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread where the message will be created. |
| threadMessageRequest | ThreadMessageCreateRequest | The request details for creating the message. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the response from the message creation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageCreateRequest](../../threadmessagecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


