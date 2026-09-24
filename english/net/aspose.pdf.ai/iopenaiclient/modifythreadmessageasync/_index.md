---
title: "IOpenAIClient.ModifyThreadMessageAsync"
linktitle: "ModifyThreadMessageAsync"
articleTitle: "ModifyThreadMessageAsync"
second_title: "Aspose.PDF for .NET"
description: "Modifies an existing message within a thread asynchronously."
type: docs
weight: 100
url: "/net/aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/"
product_version: "26.9.0"
---
## ModifyThreadMessageAsync(string, string, [ThreadMessageModifyRequest](../../../aspose.pdf.ai/threadmessagemodifyrequest/), Nullable<CancellationToken>) {#modifythreadmessageasync}

Modifies an existing message within a thread asynchronously.

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | string | The ID of the thread containing the message to modify. |
| threadMessageId | string | The ID of the message to modify. |
| threadMessageModifyRequest | ThreadMessageModifyRequest | The request details for modifying the message. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[ThreadMessageResponse](../../../aspose.pdf.ai/threadmessageresponse/)>

A task that represents the asynchronous operation. The task result contains the response from the message modification.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread message Id is null or empty. |

### See Also

* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

