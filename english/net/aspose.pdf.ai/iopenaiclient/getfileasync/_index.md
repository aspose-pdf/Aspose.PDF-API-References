---
title: IOpenAIClient.GetFileAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Retrieves details of a specific file asynchronously
type: docs
weight: 210
url: /net/aspose.pdf.ai/iopenaiclient/getfileasync/
---
## IOpenAIClient.GetFileAsync method

Retrieves details of a specific file asynchronously.

```csharp
public Task<FileResponse> GetFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileId | String | The ID of the file to retrieve. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the details of the file.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the file Id is null or empty. |

### See Also

* class [FileResponse](../../fileresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


