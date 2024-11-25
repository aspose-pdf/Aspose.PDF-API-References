---
title: IOpenAIClient.GetAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Retrieves details of a specific assistant asynchronously
type: docs
weight: 190
url: /net/aspose.pdf.ai/iopenaiclient/getassistantasync/
---
## IOpenAIClient.GetAssistantAsync method

Retrieves details of a specific assistant asynchronously.

```csharp
public Task<AssistantResponse> GetAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| assistantId | String | The ID of the assistant to retrieve. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the details of the assistant.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the assistant Id is null or empty. |

### See Also

* class [AssistantResponse](../../assistantresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


