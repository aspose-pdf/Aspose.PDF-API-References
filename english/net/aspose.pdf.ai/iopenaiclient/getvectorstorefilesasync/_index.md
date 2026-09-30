---
title: "IOpenAIClient.GetVectorStoreFilesAsync"
linktitle: "GetVectorStoreFilesAsync"
articleTitle: "GetVectorStoreFilesAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Retrieves a list of files within a specific vector store asynchronously."
type: docs
weight: 20
url: "/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/"
product_version: "26.9.0"
---
## IOpenAIClient.GetVectorStoreFilesAsync method

Retrieves a list of files within a specific vector store asynchronously.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFilesAsync(string vectorStoreId, 
    VectorStoreFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | The ID of the vector store containing the files. |
| queryParameters | VectorStoreFileListQueryParameters | Optional query parameters to filter the list of files. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains a list of files within the vector store.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the vector store Id is null or empty. |

### See Also

* class [VectorStoreFileListQueryParameters](../../../aspose.pdf.ai/vectorstorefilelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

