---
title: "OpenAIClient.DeleteVectorStoreAsync"
linktitle: "DeleteVectorStoreAsync"
articleTitle: "DeleteVectorStoreAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Deletes a vector store asynchronously."
type: docs
weight: 140
url: "/net/aspose.pdf.ai/openaiclient/deletevectorstoreasync/"
product_version: "26.9.0"
---
## DeleteVectorStoreAsync(string, Nullable<CancellationToken>) {#deletevectorstoreasync}

Deletes a vector store asynchronously.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreAsync(string vectorStoreId, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | string | The ID of the vector store to delete. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[DeleteStatusResponse](../../../aspose.pdf.ai/deletestatusresponse/)>

A task that represents the asynchronous operation. The task result contains the status of the delete operation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the vector store Id is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

