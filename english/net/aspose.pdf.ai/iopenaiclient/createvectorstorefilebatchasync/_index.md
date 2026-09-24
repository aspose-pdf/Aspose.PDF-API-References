---
title: "IOpenAIClient.CreateVectorStoreFileBatchAsync"
linktitle: "CreateVectorStoreFileBatchAsync"
articleTitle: "CreateVectorStoreFileBatchAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Creates a new vector store file batch asynchronously."
type: docs
weight: 230
url: "/net/aspose.pdf.ai/iopenaiclient/createvectorstorefilebatchasync/"
product_version: "26.9.0"
---
## CreateVectorStoreFileBatchAsync(string, [VectorStoreFileBatchCreateRequest](../../../aspose.pdf.ai/vectorstorefilebatchcreaterequest/), Nullable<CancellationToken>) {#createvectorstorefilebatchasync}

Creates a new vector store file batch asynchronously.

```csharp
public Task<VectorStoreFileBatchResponse> CreateVectorStoreFileBatchAsync(string vectorStoreId, VectorStoreFileBatchCreateRequest vectorStoreFileCreateRequest, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | string | The ID of the vector store where the file batch will be created. |
| vectorStoreFileCreateRequest | VectorStoreFileBatchCreateRequest | The request object containing details for creating the file batch. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[VectorStoreFileBatchResponse](../../../aspose.pdf.ai/vectorstorefilebatchresponse/)>

A task that represents the asynchronous operation. The task result contains the response from the file batch creation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the vector store Id is null or empty. |

### See Also

* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

