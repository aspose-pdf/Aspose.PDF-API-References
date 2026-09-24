---
title: "OpenAIClient.GetFileAsync"
linktitle: "GetFileAsync"
articleTitle: "GetFileAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Retrieves details of a specific file asynchronously."
type: docs
weight: 260
url: "/net/aspose.pdf.ai/openaiclient/getfileasync/"
product_version: "26.9.0"
---
## GetFileAsync(string, Nullable<CancellationToken>) {#getfileasync}

Retrieves details of a specific file asynchronously.

```csharp
public Task<FileResponse> GetFileAsync(string fileId, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileId | string | The ID of the file to retrieve. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[FileResponse](../../../aspose.pdf.ai/fileresponse/)>

A task that represents the asynchronous operation. The task result contains the details of the file.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the file Id is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

