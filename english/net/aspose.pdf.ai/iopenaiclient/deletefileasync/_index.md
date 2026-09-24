---
title: "IOpenAIClient.DeleteFileAsync"
linktitle: "DeleteFileAsync"
articleTitle: "DeleteFileAsync"
second_title: "Aspose.PDF for .NET"
description: "Deletes a specific file asynchronously."
type: docs
weight: 340
url: "/net/aspose.pdf.ai/iopenaiclient/deletefileasync/"
product_version: "26.9.0"
---
## DeleteFileAsync(string, Nullable<CancellationToken>) {#deletefileasync}

Deletes a specific file asynchronously.

```csharp
public Task<DeleteStatusResponse> DeleteFileAsync(string fileId, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileId | string | The ID of the file to delete. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[DeleteStatusResponse](../../../aspose.pdf.ai/deletestatusresponse/)>

A task that represents the asynchronous operation. The task result contains the status of the delete operation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the file Id is null or empty. |

### See Also

* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

