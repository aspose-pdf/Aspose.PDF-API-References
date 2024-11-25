---
title: OpenAIClient.GetFileAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient method. Retrieves details of a specific file asynchronously
type: docs
weight: 220
url: /net/aspose.pdf.ai/openaiclient/getfileasync/
---
## OpenAIClient.GetFileAsync method

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
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


