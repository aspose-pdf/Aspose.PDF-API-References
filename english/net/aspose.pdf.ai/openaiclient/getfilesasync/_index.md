---
title: "OpenAIClient.GetFilesAsync"
linktitle: "GetFilesAsync"
articleTitle: "GetFilesAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Retrieves a list of files asynchronously based on the specified purpose."
type: docs
weight: 250
url: "/net/aspose.pdf.ai/openaiclient/getfilesasync/"
product_version: "26.9.0"
---
## GetFilesAsync(string, Nullable<CancellationToken>) {#getfilesasync}

Retrieves a list of files asynchronously based on the specified purpose.

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| purpose | string | Optional. The purpose of the files to retrieve. If null, files for all purposes are retrieved. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[FileListResponse](../../../aspose.pdf.ai/filelistresponse/)>

A task that represents the asynchronous operation. The task result contains a list of files.

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

