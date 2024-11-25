---
title: IOpenAIClient.GetRunStepAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Retrieves details of a specific step within a run asynchronously
type: docs
weight: 250
url: /net/aspose.pdf.ai/iopenaiclient/getrunstepasync/
---
## IOpenAIClient.GetRunStepAsync method

Retrieves details of a specific step within a run asynchronously.

```csharp
public Task<RunStepResponse> GetRunStepAsync(string threadId, string runId, string runStepId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread containing the run. |
| runId | String | The ID of the run containing the step. |
| runStepId | String | The ID of the run step to retrieve. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the details of the run step.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the run Id is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the run step Id is null or empty. |

### See Also

* class [RunStepResponse](../../runstepresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


