---
title: IOpenAIClient.GetVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Retrieves details of a specific vector store asynchronously
type: docs
weight: 300
url: /net/aspose.pdf.ai/iopenaiclient/getvectorstoreasync/
---
## IOpenAIClient.GetVectorStoreAsync method

Retrieves details of a specific vector store asynchronously.

```csharp
public Task<VectorStoreResponse> GetVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | The ID of the vector store to retrieve. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the details of the vector store.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the vector store Id is null or empty. |

### See Also

* class [VectorStoreResponse](../../vectorstoreresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


