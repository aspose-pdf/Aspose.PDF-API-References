---
title: OpenAIClient.CancelVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient method. Cancels a specific vector store file batch asynchronously
type: docs
weight: 20
url: /net/aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/
---
## OpenAIClient.CancelVectorStoreFileBatchAsync method

Cancels a specific vector store file batch asynchronously.

```csharp
public Task<VectorStoreFileBatchResponse> CancelVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | The ID of the vector store containing the file batch to cancel. |
| fileBatchId | String | The ID of the file batch to cancel. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the response from canceling the file batch.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the vector store Id is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the vector store file batch Id is null or empty. |

### See Also

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


