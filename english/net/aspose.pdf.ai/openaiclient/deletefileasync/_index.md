---
title: "OpenAIClient.DeleteFileAsync"
linktitle: "DeleteFileAsync"
articleTitle: "DeleteFileAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Deletes a specific file asynchronously."
type: docs
weight: 270
url: "/net/aspose.pdf.ai/openaiclient/deletefileasync/"
product_version: "26.9.0"
---
## OpenAIClient.DeleteFileAsync method

Deletes a specific file asynchronously.

```csharp
public Task<DeleteStatusResponse> DeleteFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileId | String | The ID of the file to delete. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the status of the delete operation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the file Id is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

