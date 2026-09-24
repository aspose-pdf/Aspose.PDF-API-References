---
title: "IOpenAIClient.GetVectorStoreAsync"
linktitle: "GetVectorStoreAsync"
articleTitle: "GetVectorStoreAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Retrieves details of a specific vector store asynchronously."
type: docs
weight: 370
url: "/net/aspose.pdf.ai/iopenaiclient/getvectorstoreasync/"
product_version: "26.9.0"
---
## GetVectorStoreAsync(string, Nullable<CancellationToken>) {#getvectorstoreasync}

Retrieves details of a specific vector store asynchronously.

```csharp
public Task<VectorStoreResponse> GetVectorStoreAsync(string vectorStoreId, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | string | The ID of the vector store to retrieve. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[VectorStoreResponse](../../../aspose.pdf.ai/vectorstoreresponse/)>

A task that represents the asynchronous operation. The task result contains the details of the vector store.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the vector store Id is null or empty. |

### See Also

* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

