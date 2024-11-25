---
title: IOpenAIClient.DeleteVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Deletes a vector store asynchronously
type: docs
weight: 170
url: /net/aspose.pdf.ai/iopenaiclient/deletevectorstoreasync/
---
## IOpenAIClient.DeleteVectorStoreAsync method

Deletes a vector store asynchronously.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | The ID of the vector store to delete. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the status of the delete operation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the vector store Id is null or empty. |

### See Also

* class [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


