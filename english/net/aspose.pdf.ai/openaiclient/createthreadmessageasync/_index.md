---
title: "OpenAIClient.CreateThreadMessageAsync"
linktitle: "CreateThreadMessageAsync"
articleTitle: "CreateThreadMessageAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Creates a new message within a thread asynchronously."
type: docs
weight: 280
url: "/net/aspose.pdf.ai/openaiclient/createthreadmessageasync/"
product_version: "26.9.0"
---
## CreateThreadMessageAsync(string, [ThreadMessageCreateRequest](../../../aspose.pdf.ai/threadmessagecreaterequest/), Nullable<CancellationToken>) {#createthreadmessageasync}

Creates a new message within a thread asynchronously.

```csharp
public Task<ThreadMessageResponse> CreateThreadMessageAsync(string threadId, ThreadMessageCreateRequest threadMessageRequest, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | string | The ID of the thread where the message will be created. |
| threadMessageRequest | ThreadMessageCreateRequest | The request details for creating the message. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[ThreadMessageResponse](../../../aspose.pdf.ai/threadmessageresponse/)>

A task that represents the asynchronous operation. The task result contains the response from the message creation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

