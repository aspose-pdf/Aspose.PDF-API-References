---
title: IOpenAIClient.ModifyAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Modifies an existing assistant asynchronously
type: docs
weight: 360
url: /net/aspose.pdf.ai/iopenaiclient/modifyassistantasync/
---
## IOpenAIClient.ModifyAssistantAsync method

Modifies an existing assistant asynchronously.

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| assistantId | String | The ID of the assistant to modify. |
| assistantModifyRequest | AssistantModifyRequest | The request object containing modification details. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the response from the assistant modification.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the assistant Id is null or empty. |

### See Also

* class [AssistantResponse](../../assistantresponse/)
* class [AssistantModifyRequest](../../assistantmodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


