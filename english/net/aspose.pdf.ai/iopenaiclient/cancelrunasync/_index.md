---
title: "IOpenAIClient.CancelRunAsync"
linktitle: "CancelRunAsync"
articleTitle: "CancelRunAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Cancels an existing run within a thread asynchronously."
type: docs
weight: 190
url: "/net/aspose.pdf.ai/iopenaiclient/cancelrunasync/"
product_version: "26.9.0"
---
## CancelRunAsync(string, string, Nullable<CancellationToken>) {#cancelrunasync}

Cancels an existing run within a thread asynchronously.

```csharp
public Task<RunResponse> CancelRunAsync(string threadId, string runId, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | string | The ID of the thread containing the run to cancel. |
| runId | string | The ID of the run to cancel. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[RunResponse](../../../aspose.pdf.ai/runresponse/)>

A task that represents the asynchronous operation. The task result contains the response from the run cancellation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the run Id is null or empty. |

### See Also

* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

