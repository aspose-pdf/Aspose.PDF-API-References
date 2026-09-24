---
title: "OpenAIClient.GetVectorStoreFilesAsync"
linktitle: "GetVectorStoreFilesAsync"
articleTitle: "GetVectorStoreFilesAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Retrieves a list of files within a specific vector store asynchronously."
type: docs
weight: 60
url: "/net/aspose.pdf.ai/openaiclient/getvectorstorefilesasync/"
product_version: "26.9.0"
---
## GetVectorStoreFilesAsync(string, [VectorStoreFileListQueryParameters](../../../aspose.pdf.ai/vectorstorefilelistqueryparameters/), Nullable<CancellationToken>) {#getvectorstorefilesasync}

Retrieves a list of files within a specific vector store asynchronously.

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFilesAsync(string vectorStoreId, VectorStoreFileListQueryParameters queryParameters, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | string | The ID of the vector store containing the files. |
| queryParameters | VectorStoreFileListQueryParameters | Optional query parameters to filter the list of files. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[VectorStoreFileListResponse](../../../aspose.pdf.ai/vectorstorefilelistresponse/)>

A task that represents the asynchronous operation. The task result contains a list of files within the vector store.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the vector store Id is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

