---
title: "IOpenAIClient.WaitForAssistantMessageAsync"
linktitle: "WaitForAssistantMessageAsync"
articleTitle: "WaitForAssistantMessageAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Waits for the first message from the assistant within a thread asynchronously."
type: docs
weight: 130
url: "/net/aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/"
product_version: "26.9.0"
---
## WaitForAssistantMessageAsync(string, [ThreadMessageListQueryParameters](../../../aspose.pdf.ai/threadmessagelistqueryparameters/), Nullable<CancellationToken>) {#waitforassistantmessageasync}

Waits for the first message from the assistant within a thread asynchronously.

```csharp
public Task<ThreadMessageResponse> WaitForAssistantMessageAsync(string threadId, ThreadMessageListQueryParameters queryParameters, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | string | The ID of the thread to monitor for the first assistant message. |
| queryParameters | ThreadMessageListQueryParameters | Optional query parameters to filter the list of messages. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[ThreadMessageResponse](../../../aspose.pdf.ai/threadmessageresponse/)>

A task that represents the asynchronous operation. The task result contains the first assistant message in the thread.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also

* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

