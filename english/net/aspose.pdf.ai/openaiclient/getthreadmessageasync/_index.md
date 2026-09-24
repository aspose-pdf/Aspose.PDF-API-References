---
title: "OpenAIClient.GetThreadMessageAsync"
linktitle: "GetThreadMessageAsync"
articleTitle: "GetThreadMessageAsync"
second_title: "Aspose.PDF for .NET"
description: "Retrieves details of a specific message within a thread asynchronously."
type: docs
weight: 300
url: "/net/aspose.pdf.ai/openaiclient/getthreadmessageasync/"
product_version: "26.9.0"
---
## GetThreadMessageAsync(string, string, Nullable<CancellationToken>) {#getthreadmessageasync}

Retrieves details of a specific message within a thread asynchronously.

```csharp
public Task<ThreadMessageResponse> GetThreadMessageAsync(string threadId, string threadMessageId, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | string | The ID of the thread containing the message. |
| threadMessageId | string | The ID of the message to retrieve. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[ThreadMessageResponse](../../../aspose.pdf.ai/threadmessageresponse/)>

A task that represents the asynchronous operation. The task result contains the details of the thread message.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread message Id is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

