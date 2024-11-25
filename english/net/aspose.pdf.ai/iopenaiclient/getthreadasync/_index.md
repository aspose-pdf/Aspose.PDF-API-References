---
title: IOpenAIClient.GetThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Retrieves details of a specific thread asynchronously
type: docs
weight: 270
url: /net/aspose.pdf.ai/iopenaiclient/getthreadasync/
---
## IOpenAIClient.GetThreadAsync method

Retrieves details of a specific thread asynchronously.

```csharp
public Task<ThreadResponse> GetThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread to retrieve. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the details of the thread.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also

* class [ThreadResponse](../../threadresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


