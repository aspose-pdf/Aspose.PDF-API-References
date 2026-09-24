---
title: "IOpenAIClient.GetVectorStoreFileAsync"
linktitle: "GetVectorStoreFileAsync"
articleTitle: "GetVectorStoreFileAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Retrieves details of a specific file within a vector store asynchronously."
type: docs
weight: 30
url: "/net/aspose.pdf.ai/iopenaiclient/getvectorstorefileasync/"
product_version: "26.9.0"
---
## GetVectorStoreFileAsync(string, string, Nullable<CancellationToken>) {#getvectorstorefileasync}

Retrieves details of a specific file within a vector store asynchronously.

```csharp
public Task<VectorStoreFileResponse> GetVectorStoreFileAsync(string vectorStoreId, string fileId, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | string | The ID of the vector store containing the file. |
| fileId | string | The ID of the file to retrieve. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[VectorStoreFileResponse](../../../aspose.pdf.ai/vectorstorefileresponse/)>

A task that represents the asynchronous operation. The task result contains the details of the file.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the vector store Id is null or empty. |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the file Id is null or empty. |

### See Also

* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

