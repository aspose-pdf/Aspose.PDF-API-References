---
title: "OpenAIClient.WaitForRunToCompleteAsync"
linktitle: "WaitForRunToCompleteAsync"
articleTitle: "WaitForRunToCompleteAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Waits for a run to complete within a thread asynchronously."
type: docs
weight: 510
url: "/net/aspose.pdf.ai/openaiclient/waitforruntocompleteasync/"
product_version: "26.9.0"
---
## OpenAIClient.WaitForRunToCompleteAsync method

Waits for a run to complete within a thread asynchronously.

```csharp
public Task<RunResponse> WaitForRunToCompleteAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread containing the run. |
| runId | String | The ID of the run to monitor until completion. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the final status of the run.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the run Id is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

