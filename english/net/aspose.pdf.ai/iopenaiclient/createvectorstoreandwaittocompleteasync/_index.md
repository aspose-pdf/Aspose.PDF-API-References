---
title: IOpenAIClient.CreateVectorStoreAndWaitToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Creates a new vector store and waits for it to complete asynchronously
type: docs
weight: 90
url: /net/aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync/
---
## IOpenAIClient.CreateVectorStoreAndWaitToCompleteAsync method

Creates a new vector store and waits for it to complete asynchronously.

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAndWaitToCompleteAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | The request object containing details for creating the vector store. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the response from the vector store creation after completion.

### See Also

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


