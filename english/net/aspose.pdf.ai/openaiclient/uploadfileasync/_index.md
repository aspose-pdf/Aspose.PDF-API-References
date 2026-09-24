---
title: "OpenAIClient.UploadFileAsync"
linktitle: "UploadFileAsync"
articleTitle: "UploadFileAsync"
second_title: "Aspose.PDF for .NET"
description: "Uploads a file asynchronously to the OpenAI server."
type: docs
weight: 240
url: "/net/aspose.pdf.ai/openaiclient/uploadfileasync/"
product_version: "26.9.0"
---
## UploadFileAsync(string, string, byte[], Nullable<CancellationToken>) {#uploadfileasync}

Uploads a file asynchronously to the OpenAI server.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| purpose | string | The purpose of the file upload, typically describing how the file will be used. |
| fileName | string | The name of the file to upload. |
| fileBytes | byte[] | The byte array containing the file data. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[FileResponse](../../../aspose.pdf.ai/fileresponse/)>

A task that represents the asynchronous operation. The task result contains the response from the file upload.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the file purpose is null or empty. |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the file name is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

