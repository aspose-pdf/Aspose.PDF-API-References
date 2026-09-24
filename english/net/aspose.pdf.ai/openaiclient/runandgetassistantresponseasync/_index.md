---
title: "OpenAIClient.RunAndGetAssistantResponseAsync"
linktitle: "RunAndGetAssistantResponseAsync"
articleTitle: "RunAndGetAssistantResponseAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Runs the assistant with the specified threadId and runCreateRequest, and asynchronously gets the assistant response."
type: docs
weight: 520
url: "/net/aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/"
product_version: "26.9.0"
---
## RunAndGetAssistantResponseAsync(string, [RunCreateRequest](../../../aspose.pdf.ai/runcreaterequest/), Nullable<CancellationToken>) {#runandgetassistantresponseasync}

Runs the assistant with the specified threadId and runCreateRequest, and asynchronously gets the assistant response.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, RunCreateRequest runCreateRequest, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | string | The ID of the thread. |
| runCreateRequest | RunCreateRequest | The run creation request. |
| cancellationToken | Nullable<CancellationToken> | The cancellation token (optional). |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<string>

A task representing the asynchronous operation with the assistant response string.

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

