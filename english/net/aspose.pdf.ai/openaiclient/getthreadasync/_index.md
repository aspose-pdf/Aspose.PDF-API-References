---
title: "OpenAIClient.GetThreadAsync"
linktitle: "GetThreadAsync"
articleTitle: "GetThreadAsync"
second_title: "Aspose.PDF for .NET"
description: "Retrieves details of a specific thread asynchronously."
type: docs
weight: 360
url: "/net/aspose.pdf.ai/openaiclient/getthreadasync/"
product_version: "26.9.0"
---
## GetThreadAsync(string, Nullable<CancellationToken>) {#getthreadasync}

Retrieves details of a specific thread asynchronously.

```csharp
public Task<ThreadResponse> GetThreadAsync(string threadId, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | string | The ID of the thread to retrieve. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[ThreadResponse](../../../aspose.pdf.ai/threadresponse/)>

A task that represents the asynchronous operation. The task result contains the details of the thread.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

