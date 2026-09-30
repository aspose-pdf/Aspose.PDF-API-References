---
title: "OpenAIClient.GetThreadMessagesAsync"
linktitle: "GetThreadMessagesAsync"
articleTitle: "GetThreadMessagesAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Retrieves a list of messages for a specific thread asynchronously."
type: docs
weight: 290
url: "/net/aspose.pdf.ai/openaiclient/getthreadmessagesasync/"
product_version: "26.9.0"
---
## OpenAIClient.GetThreadMessagesAsync method

Retrieves a list of messages for a specific thread asynchronously.

```csharp
public Task<ThreadMessageListResponse> GetThreadMessagesAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread to retrieve messages from. |
| queryParameters | ThreadMessageListQueryParameters | Optional query parameters to filter the list of messages. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains a list of thread messages.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also

* class [ThreadMessageListQueryParameters](../../../aspose.pdf.ai/threadmessagelistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

