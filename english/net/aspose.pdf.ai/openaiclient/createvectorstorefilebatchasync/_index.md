---
title: OpenAIClient.CreateVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient method. Creates a new vector store file batch asynchronously
type: docs
weight: 120
url: /net/aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/
---
## OpenAIClient.CreateVectorStoreFileBatchAsync method

Creates a new vector store file batch asynchronously.

```csharp
public Task<VectorStoreFileBatchResponse> CreateVectorStoreFileBatchAsync(string vectorStoreId, 
    VectorStoreFileBatchCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | The ID of the vector store where the file batch will be created. |
| vectorStoreFileCreateRequest | VectorStoreFileBatchCreateRequest | The request object containing details for creating the file batch. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the response from the file batch creation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the vector store Id is null or empty. |

### See Also

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* class [VectorStoreFileBatchCreateRequest](../../vectorstorefilebatchcreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


