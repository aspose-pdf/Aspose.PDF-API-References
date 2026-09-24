---
title: "OpenAIClient.ModifyRunAsync"
linktitle: "ModifyRunAsync"
articleTitle: "ModifyRunAsync"
second_title: "Aspose.PDF for .NET"
description: "Modifies an existing run within a thread asynchronously."
type: docs
weight: 490
url: "/net/aspose.pdf.ai/openaiclient/modifyrunasync/"
product_version: "26.9.0"
---
## ModifyRunAsync(string, string, [RunModifyRequest](../../../aspose.pdf.ai/runmodifyrequest/), Nullable<CancellationToken>) {#modifyrunasync}

Modifies an existing run within a thread asynchronously.

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, RunModifyRequest assistantModifyRequest, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | string | The ID of the thread containing the run. |
| runId | string | The ID of the run to modify. |
| assistantModifyRequest | RunModifyRequest | The request details for modifying the run. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[RunResponse](../../../aspose.pdf.ai/runresponse/)>

A task that represents the asynchronous operation. The task result contains the response from the run modification.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread Id is null or empty. |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the run Id is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

