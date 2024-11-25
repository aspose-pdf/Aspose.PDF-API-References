---
title: IOpenAIClient.DeleteAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Deletes an existing assistant asynchronously
type: docs
weight: 130
url: /net/aspose.pdf.ai/iopenaiclient/deleteassistantasync/
---
## IOpenAIClient.DeleteAssistantAsync method

Deletes an existing assistant asynchronously.

```csharp
public Task<DeleteStatusResponse> DeleteAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| assistantId | String | The ID of the assistant to delete. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the status of the delete operation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the assistant Id is null or empty. |

### See Also

* class [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


