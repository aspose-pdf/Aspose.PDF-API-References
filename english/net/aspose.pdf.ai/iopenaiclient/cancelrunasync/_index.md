---
title: IOpenAIClient.CancelRunAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Cancels an existing run within a thread asynchronously
type: docs
weight: 10
url: /net/aspose.pdf.ai/iopenaiclient/cancelrunasync/
---
## IOpenAIClient.CancelRunAsync method

Cancels an existing run within a thread asynchronously.

```csharp
public Task<RunResponse> CancelRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread containing the run to cancel. |
| runId | String | The ID of the run to cancel. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the response from the run cancellation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the run Id is null or empty. |

### See Also

* class [RunResponse](../../runresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


