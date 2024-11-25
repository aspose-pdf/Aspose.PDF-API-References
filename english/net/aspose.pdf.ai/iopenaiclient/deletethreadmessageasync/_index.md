---
title: IOpenAIClient.DeleteThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Deletes a message within a thread asynchronously
type: docs
weight: 160
url: /net/aspose.pdf.ai/iopenaiclient/deletethreadmessageasync/
---
## IOpenAIClient.DeleteThreadMessageAsync method

Deletes a message within a thread asynchronously.

```csharp
public Task<DeleteStatusResponse> DeleteThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread containing the message to delete. |
| threadMessageId | String | The ID of the message to delete. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the status of the delete operation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the thread message Id is null or empty. |

### See Also

* class [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


