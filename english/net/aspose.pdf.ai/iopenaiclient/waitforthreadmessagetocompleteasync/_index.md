---
title: "IOpenAIClient.WaitForThreadMessageToCompleteAsync"
linktitle: "WaitForThreadMessageToCompleteAsync"
articleTitle: "WaitForThreadMessageToCompleteAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Waits for a specific thread message to complete asynchronously."
type: docs
weight: 120
url: "/net/aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/"
product_version: "26.9.0"
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
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread message Id is null or empty. |

### See Also

* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

