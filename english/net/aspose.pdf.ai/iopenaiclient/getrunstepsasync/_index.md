---
title: IOpenAIClient.GetRunStepsAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Retrieves a list of steps for a specific run within a thread asynchronously
type: docs
weight: 260
url: /net/aspose.pdf.ai/iopenaiclient/getrunstepsasync/
---
## IOpenAIClient.GetRunStepsAsync method

Retrieves a list of steps for a specific run within a thread asynchronously.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread containing the run. |
| runId | String | The ID of the run to retrieve steps from. |
| queryParameters | RunStepListQueryParameters | Optional query parameters to filter the list of run steps. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the list of run steps.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the run Id is null or empty. |

### See Also

* class [RunStepListResponse](../../runsteplistresponse/)
* class [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


