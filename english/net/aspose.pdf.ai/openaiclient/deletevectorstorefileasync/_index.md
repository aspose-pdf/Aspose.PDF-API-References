---
title: "OpenAIClient.DeleteVectorStoreFileAsync"
linktitle: "DeleteVectorStoreFileAsync"
articleTitle: "DeleteVectorStoreFileAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Deletes a file within a vector store asynchronously."
type: docs
weight: 80
url: "/net/aspose.pdf.ai/openaiclient/deletevectorstorefileasync/"
product_version: "26.9.0"
---
## DeleteVectorStoreFileAsync(string, string, Nullable<CancellationToken>) {#deletevectorstorefileasync}

Deletes a file within a vector store asynchronously.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreFileAsync(string vectorStoreId, string fileId, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | string | The ID of the vector store containing the file to delete. |
| fileId | string | The ID of the file to delete. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[DeleteStatusResponse](../../../aspose.pdf.ai/deletestatusresponse/)>

A task that represents the asynchronous operation. The task result contains the status of the delete operation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the vector store Id is null or empty. |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the file Id is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

