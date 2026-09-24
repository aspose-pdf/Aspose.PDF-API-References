---
title: "OpenAIClient.WaitForThreadMessageToCompleteAsync"
linktitle: "WaitForThreadMessageToCompleteAsync"
articleTitle: "WaitForThreadMessageToCompleteAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Waits for a specific thread message to complete asynchronously."
type: docs
weight: 330
url: "/net/aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/"
product_version: "26.9.0"
---
## WaitForThreadMessageToCompleteAsync(string, string, Nullable<CancellationToken>) {#waitforthreadmessagetocompleteasync}

Waits for a specific thread message to complete asynchronously.

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, string threadMessageId, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | string | The ID of the thread containing the message. |
| threadMessageId | string | The ID of the message to monitor until completion. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[ThreadMessageResponse](../../../aspose.pdf.ai/threadmessageresponse/)>

A task that represents the asynchronous operation. The task result contains the final status of the message.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread message Id is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

