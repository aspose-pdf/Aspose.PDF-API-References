---
title: IOpenAIClient.DeleteThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Deletes an existing thread asynchronously
type: docs
weight: 150
url: /net/aspose.pdf.ai/iopenaiclient/deletethreadasync/
---
## IOpenAIClient.DeleteThreadAsync method

Deletes an existing thread asynchronously.

```csharp
public Task<DeleteStatusResponse> DeleteThreadAsync(string threadId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread to delete. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the status of the delete operation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also

* class [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


