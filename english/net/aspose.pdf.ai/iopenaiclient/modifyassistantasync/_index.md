---
title: "IOpenAIClient.ModifyAssistantAsync"
linktitle: "ModifyAssistantAsync"
articleTitle: "ModifyAssistantAsync"
second_title: "Aspose.PDF for .NET"
description: "Modifies an existing assistant asynchronously."
type: docs
weight: 450
url: "/net/aspose.pdf.ai/iopenaiclient/modifyassistantasync/"
product_version: "26.9.0"
---
## ModifyAssistantAsync(string, [AssistantModifyRequest](../../../aspose.pdf.ai/assistantmodifyrequest/), Nullable<CancellationToken>) {#modifyassistantasync}

Modifies an existing assistant asynchronously.

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, AssistantModifyRequest assistantModifyRequest, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| assistantId | string | The ID of the assistant to modify. |
| assistantModifyRequest | AssistantModifyRequest | The request object containing modification details. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[AssistantResponse](../../../aspose.pdf.ai/assistantresponse/)>

A task that represents the asynchronous operation. The task result contains the response from the assistant modification.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the assistant Id is null or empty. |

### See Also

* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

