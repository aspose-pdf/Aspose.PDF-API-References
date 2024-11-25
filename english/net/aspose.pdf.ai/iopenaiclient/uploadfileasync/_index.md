---
title: IOpenAIClient.UploadFileAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Uploads a file asynchronously to the OpenAI server
type: docs
weight: 420
url: /net/aspose.pdf.ai/iopenaiclient/uploadfileasync/
---
## IOpenAIClient.UploadFileAsync method

Uploads a file asynchronously to the OpenAI server.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| purpose | String | The purpose of the file upload, typically describing how the file will be used. |
| fileName | String | The name of the file to upload. |
| fileBytes | Byte[] | The byte array containing the file data. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the response from the file upload.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the file purpose is null or empty. |
| [AIClientException](../../aiclientexception/) | Thrown when the file name is null or empty. |

### See Also

* class [FileResponse](../../fileresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


