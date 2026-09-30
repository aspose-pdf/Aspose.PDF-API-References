---
title: "OpenAIClient.DeleteAssistantAsync"
linktitle: "DeleteAssistantAsync"
articleTitle: "DeleteAssistantAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Deletes an existing assistant asynchronously."
type: docs
weight: 430
url: "/net/aspose.pdf.ai/openaiclient/deleteassistantasync/"
product_version: "26.9.0"
---
## OpenAIClient.DeleteAssistantAsync method

Deletes an existing assistant asynchronously.

```csharp
public Task<DeleteStatusResponse> DeleteAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| assistantId | String | The ID of the assistant to delete. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the status of the delete operation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the assistant Id is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

