---
title: "IOpenAIClient.DeleteThreadMessageAsync"
linktitle: "DeleteThreadMessageAsync"
articleTitle: "DeleteThreadMessageAsync"
second_title: "Aspose.PDF for .NET"
description: "Deletes a message within a thread asynchronously."
type: docs
weight: 110
url: "/net/aspose.pdf.ai/iopenaiclient/deletethreadmessageasync/"
product_version: "26.9.0"
---
## DeleteThreadMessageAsync(string, string, Nullable<CancellationToken>) {#deletethreadmessageasync}

Deletes a message within a thread asynchronously.

```csharp
public Task<DeleteStatusResponse> DeleteThreadMessageAsync(string threadId, string threadMessageId, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | string | The ID of the thread containing the message to delete. |
| threadMessageId | string | The ID of the message to delete. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[DeleteStatusResponse](../../../aspose.pdf.ai/deletestatusresponse/)>

A task that represents the asynchronous operation. The task result contains the status of the delete operation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread message Id is null or empty. |

### See Also

* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

