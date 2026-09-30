---
title: "OpenAIClient.GetAssistantAsync"
linktitle: "GetAssistantAsync"
articleTitle: "GetAssistantAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Retrieves details of a specific assistant asynchronously."
type: docs
weight: 410
url: "/net/aspose.pdf.ai/openaiclient/getassistantasync/"
product_version: "26.9.0"
---
## OpenAIClient.GetAssistantAsync method

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
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the assistant Id is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

