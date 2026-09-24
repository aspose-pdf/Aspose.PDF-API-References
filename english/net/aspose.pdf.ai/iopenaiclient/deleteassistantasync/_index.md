---
title: "IOpenAIClient.DeleteAssistantAsync"
linktitle: "DeleteAssistantAsync"
articleTitle: "DeleteAssistantAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Deletes an existing assistant asynchronously."
type: docs
weight: 460
url: "/net/aspose.pdf.ai/iopenaiclient/deleteassistantasync/"
product_version: "26.9.0"
---
## DeleteAssistantAsync(string, Nullable<CancellationToken>) {#deleteassistantasync}

Deletes an existing assistant asynchronously.

```csharp
public Task<DeleteStatusResponse> DeleteAssistantAsync(string assistantId, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| assistantId | string | The ID of the assistant to delete. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[DeleteStatusResponse](../../../aspose.pdf.ai/deletestatusresponse/)>

A task that represents the asynchronous operation. The task result contains the status of the delete operation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the assistant Id is null or empty. |

### See Also

* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

