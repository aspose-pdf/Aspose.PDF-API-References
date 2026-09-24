---
title: "IOpenAIClient.GetVectorStoreFileBatchFilesAsync"
linktitle: "GetVectorStoreFileBatchFilesAsync"
articleTitle: "GetVectorStoreFileBatchFilesAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Retrieves a list of files within a specific vector store file batch asynchronously."
type: docs
weight: 260
url: "/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/"
product_version: "26.9.0"
---
## GetVectorStoreFileBatchFilesAsync(string, string, [VectorStoreFileBatchFileListQueryParameters](../../../aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/), Nullable<CancellationToken>) {#getvectorstorefilebatchfilesasync}

Retrieves a list of files within a specific vector store file batch asynchronously.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | string | The ID of the vector store containing the file batch. |
| fileBatchId | string | The ID of the file batch to retrieve files from. |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | Optional query parameters to filter the list of files. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[VectorStoreFileListResponse](../../../aspose.pdf.ai/vectorstorefilelistresponse/)>

A task that represents the asynchronous operation. The task result contains a list of files within the file batch.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the vector store Id is null or empty. |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the vector store file batch Id is null or empty. |

### See Also

* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

