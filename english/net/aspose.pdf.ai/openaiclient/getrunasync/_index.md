---
title: "OpenAIClient.GetRunAsync"
linktitle: "GetRunAsync"
articleTitle: "GetRunAsync"
second_title: "Aspose.PDF for .NET"
description: "Retrieves details of a specific run within a thread asynchronously."
type: docs
weight: 480
url: "/net/aspose.pdf.ai/openaiclient/getrunasync/"
product_version: "26.9.0"
---
## GetRunAsync(string, string, Nullable<CancellationToken>) {#getrunasync}

Retrieves details of a specific run within a thread asynchronously.

```csharp
public Task<RunResponse> GetRunAsync(string threadId, string runId, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | string | The ID of the thread containing the run. |
| runId | string | The ID of the run to retrieve. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[RunResponse](../../../aspose.pdf.ai/runresponse/)>

A task that represents the asynchronous operation. The task result contains the details of the run.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the run Id is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

