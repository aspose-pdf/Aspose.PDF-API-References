---
title: "IOpenAIClient.CancelVectorStoreFileBatchAsync"
linktitle: "CancelVectorStoreFileBatchAsync"
articleTitle: "CancelVectorStoreFileBatchAsync"
second_title: "Aspose.PDF for .NET"
description: "Cancels a specific vector store file batch asynchronously."
type: docs
weight: 250
url: "/net/aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/"
product_version: "26.9.0"
---
## CancelVectorStoreFileBatchAsync(string, string, Nullable<CancellationToken>) {#cancelvectorstorefilebatchasync}

Cancels a specific vector store file batch asynchronously.

```csharp
public Task<VectorStoreFileBatchResponse> CancelVectorStoreFileBatchAsync(string vectorStoreId, string fileBatchId, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | string | The ID of the vector store containing the file batch to cancel. |
| fileBatchId | string | The ID of the file batch to cancel. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[VectorStoreFileBatchResponse](../../../aspose.pdf.ai/vectorstorefilebatchresponse/)>

A task that represents the asynchronous operation. The task result contains the response from canceling the file batch.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the vector store Id is null or empty. |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the vector store file batch Id is null or empty. |

### See Also

* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

