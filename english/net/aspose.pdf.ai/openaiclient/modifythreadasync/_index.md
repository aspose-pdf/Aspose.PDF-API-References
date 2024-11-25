---
title: OpenAIClient.ModifyThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient method. Modifies an existing thread asynchronously
type: docs
weight: 410
url: /net/aspose.pdf.ai/openaiclient/modifythreadasync/
---
## OpenAIClient.ModifyThreadAsync method

Modifies an existing thread asynchronously.

```csharp
public Task<ThreadResponse> ModifyThreadAsync(string threadId, 
    ThreadModifyRequest threadModifyRequest, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread to modify. |
| threadModifyRequest | ThreadModifyRequest | The request object containing modification details. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the response from the thread modification.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also

* class [ThreadResponse](../../threadresponse/)
* class [ThreadModifyRequest](../../threadmodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


