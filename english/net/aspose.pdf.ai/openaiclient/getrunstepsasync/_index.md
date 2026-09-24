---
title: "OpenAIClient.GetRunStepsAsync"
linktitle: "GetRunStepsAsync"
articleTitle: "GetRunStepsAsync"
second_title: "Aspose.PDF for .NET"
description: "Retrieves a list of steps for a specific run within a thread asynchronously."
type: docs
weight: 220
url: "/net/aspose.pdf.ai/openaiclient/getrunstepsasync/"
product_version: "26.9.0"
---
## GetRunStepsAsync(string, string, [RunStepListQueryParameters](../../../aspose.pdf.ai/runsteplistqueryparameters/), Nullable<CancellationToken>) {#getrunstepsasync}

Retrieves a list of steps for a specific run within a thread asynchronously.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, RunStepListQueryParameters queryParameters, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | string | The ID of the thread containing the run. |
| runId | string | The ID of the run to retrieve steps from. |
| queryParameters | RunStepListQueryParameters | Optional query parameters to filter the list of run steps. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[RunStepListResponse](../../../aspose.pdf.ai/runsteplistresponse/)>

A task that represents the asynchronous operation. The task result contains the list of run steps.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the run Id is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

