---
title: "OpenAIClient.GetAssistantAsync"
linktitle: "GetAssistantAsync"
articleTitle: "GetAssistantAsync"
second_title: "Aspose.PDF for .NET"
description: "Retrieves details of a specific assistant asynchronously."
type: docs
weight: 410
url: "/net/aspose.pdf.ai/openaiclient/getassistantasync/"
product_version: "26.9.0"
---
## GetAssistantAsync(string, Nullable<CancellationToken>) {#getassistantasync}

Retrieves details of a specific assistant asynchronously.

```csharp
public Task<AssistantResponse> GetAssistantAsync(string assistantId, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| assistantId | string | The ID of the assistant to retrieve. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[AssistantResponse](../../../aspose.pdf.ai/assistantresponse/)>

A task that represents the asynchronous operation. The task result contains the details of the assistant.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the assistant Id is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

