---
title: IOpenAIClient.ModifyVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Modifies an existing vector store asynchronously
type: docs
weight: 400
url: /net/aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/
---
## IOpenAIClient.ModifyVectorStoreAsync method

Modifies an existing vector store asynchronously.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | The ID of the vector store to modify. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | The request object containing modification details. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the response from the vector store modification.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the vector store Id is null or empty. |

### See Also

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


