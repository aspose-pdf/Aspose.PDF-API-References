---
title: "OpenAIClient.GetRunsAsync"
linktitle: "GetRunsAsync"
articleTitle: "GetRunsAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Retrieves a list of runs for a specified thread asynchronously."
type: docs
weight: 470
url: "/net/aspose.pdf.ai/openaiclient/getrunsasync/"
product_version: "26.9.0"
---
## GetRunsAsync(string, [RunListQueryParameters](../../../aspose.pdf.ai/runlistqueryparameters/), Nullable<CancellationToken>) {#getrunsasync}

Retrieves a list of runs for a specified thread asynchronously.

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, RunListQueryParameters queryParameters, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | string | The ID of the thread to retrieve runs from. |
| queryParameters | RunListQueryParameters | Optional query parameters to filter the list of runs. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[RunListResponse](../../../aspose.pdf.ai/runlistresponse/)>

A task that represents the asynchronous operation. The task result contains a list of runs.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

