---
title: IOpenAIClient.CreateRunAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Creates a run within a specified thread asynchronously
type: docs
weight: 50
url: /net/aspose.pdf.ai/iopenaiclient/createrunasync/
---
## IOpenAIClient.CreateRunAsync method

Creates a run within a specified thread asynchronously.

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread where the run will be created. |
| runCreateRequest | RunCreateRequest | The request details for creating the run. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the response from the run creation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also

* class [RunResponse](../../runresponse/)
* class [RunCreateRequest](../../runcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


