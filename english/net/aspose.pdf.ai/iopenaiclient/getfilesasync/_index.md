---
title: IOpenAIClient.GetFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Retrieves a list of files asynchronously based on the specified purpose
type: docs
weight: 220
url: /net/aspose.pdf.ai/iopenaiclient/getfilesasync/
---
## IOpenAIClient.GetFilesAsync method

Retrieves a list of files asynchronously based on the specified purpose.

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| purpose | String | Optional. The purpose of the files to retrieve. If null, files for all purposes are retrieved. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains a list of files.

### See Also

* class [FileListResponse](../../filelistresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


