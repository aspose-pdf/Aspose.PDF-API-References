---
title: IOpenAIClient.GetAssistantsAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient method. Retrieves a list of assistants asynchronously
type: docs
weight: 200
url: /net/aspose.pdf.ai/iopenaiclient/getassistantsasync/
---
## IOpenAIClient.GetAssistantsAsync method

Retrieves a list of assistants asynchronously.

```csharp
public Task<AssistantListResponse> GetAssistantsAsync(
    AssistantListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| queryParameters | AssistantListQueryParameters | Optional query parameters to filter the list of assistants. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the list of assistants.

### See Also

* class [AssistantListResponse](../../assistantlistresponse/)
* class [AssistantListQueryParameters](../../assistantlistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


