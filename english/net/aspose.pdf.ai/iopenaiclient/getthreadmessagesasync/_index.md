---
title: "IOpenAIClient.GetThreadMessagesAsync"
linktitle: "GetThreadMessagesAsync"
articleTitle: "GetThreadMessagesAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Retrieves a list of messages for a specific thread asynchronously."
type: docs
weight: 80
url: "/net/aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/"
product_version: "26.9.0"
---
## GetThreadMessagesAsync(string, [ThreadMessageListQueryParameters](../../../aspose.pdf.ai/threadmessagelistqueryparameters/), Nullable<CancellationToken>) {#getthreadmessagesasync}

Retrieves a list of messages for a specific thread asynchronously.

```csharp
public Task<ThreadMessageListResponse> GetThreadMessagesAsync(string threadId, ThreadMessageListQueryParameters queryParameters, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | string | The ID of the thread to retrieve messages from. |
| queryParameters | ThreadMessageListQueryParameters | Optional query parameters to filter the list of messages. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[ThreadMessageListResponse](../../../aspose.pdf.ai/threadmessagelistresponse/)>

A task that represents the asynchronous operation. The task result contains a list of thread messages.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also

* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

