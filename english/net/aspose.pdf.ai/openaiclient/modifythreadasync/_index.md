---
title: "OpenAIClient.ModifyThreadAsync"
linktitle: "ModifyThreadAsync"
articleTitle: "ModifyThreadAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Modifies an existing thread asynchronously."
type: docs
weight: 370
url: "/net/aspose.pdf.ai/openaiclient/modifythreadasync/"
product_version: "26.9.0"
---
## ModifyThreadAsync(string, [ThreadModifyRequest](../../../aspose.pdf.ai/threadmodifyrequest/), Nullable<CancellationToken>) {#modifythreadasync}

Modifies an existing thread asynchronously.

```csharp
public Task<ThreadResponse> ModifyThreadAsync(string threadId, ThreadModifyRequest threadModifyRequest, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | string | The ID of the thread to modify. |
| threadModifyRequest | ThreadModifyRequest | The request object containing modification details. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[ThreadResponse](../../../aspose.pdf.ai/threadresponse/)>

A task that represents the asynchronous operation. The task result contains the response from the thread modification.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

