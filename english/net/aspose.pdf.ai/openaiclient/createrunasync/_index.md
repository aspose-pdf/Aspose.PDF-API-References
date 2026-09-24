---
title: "OpenAIClient.CreateRunAsync"
linktitle: "CreateRunAsync"
articleTitle: "CreateRunAsync"
second_title: "Aspose.PDF for .NET"
description: "Creates a run within a specified thread asynchronously."
type: docs
weight: 450
url: "/net/aspose.pdf.ai/openaiclient/createrunasync/"
product_version: "26.9.0"
---
## CreateRunAsync(string, [RunCreateRequest](../../../aspose.pdf.ai/runcreaterequest/), Nullable<CancellationToken>) {#createrunasync}

Creates a run within a specified thread asynchronously.

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | string | The ID of the thread where the run will be created. |
| runCreateRequest | RunCreateRequest | The request details for creating the run. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[RunResponse](../../../aspose.pdf.ai/runresponse/)>

A task that represents the asynchronous operation. The task result contains the response from the run creation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

