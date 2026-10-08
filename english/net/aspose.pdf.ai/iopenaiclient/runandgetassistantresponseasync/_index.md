---
title: "IOpenAIClient.RunAndGetAssistantResponseAsync"
linktitle: "RunAndGetAssistantResponseAsync"
articleTitle: "RunAndGetAssistantResponseAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Runs the assistant with the specified threadId and runCreateRequest, and asynchronously gets the assistant response."
type: docs
weight: 470
url: "/net/aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/"
product_version: "26.9"
---
## IOpenAIClient.RunAndGetAssistantResponseAsync method

Runs the assistant with the specified threadId and runCreateRequest, and asynchronously gets the assistant response.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread. |
| runCreateRequest | RunCreateRequest | The run creation request. |
| cancellationToken | Nullable`1 | The cancellation token (optional). |

### Return Value

A task representing the asynchronous operation with the assistant response string.

### See Also

* class [RunCreateRequest](../../runcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

