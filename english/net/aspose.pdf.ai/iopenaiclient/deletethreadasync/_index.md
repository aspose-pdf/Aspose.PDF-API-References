---
title: "IOpenAIClient.DeleteThreadAsync"
linktitle: "DeleteThreadAsync"
articleTitle: "DeleteThreadAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Deletes an existing thread asynchronously."
type: docs
weight: 300
url: "/net/aspose.pdf.ai/iopenaiclient/deletethreadasync/"
product_version: "26.9.0"
---
## DeleteThreadAsync(string, Nullable<CancellationToken>) {#deletethreadasync}

Deletes an existing thread asynchronously.

```csharp
public Task<DeleteStatusResponse> DeleteThreadAsync(string threadId, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | string | The ID of the thread to delete. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[DeleteStatusResponse](../../../aspose.pdf.ai/deletestatusresponse/)>

A task that represents the asynchronous operation. The task result contains the status of the delete operation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also

* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

