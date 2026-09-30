---
title: "IOpenAIClient.GetRunsAsync"
linktitle: "GetRunsAsync"
articleTitle: "GetRunsAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Retrieves a list of runs for a specified thread asynchronously."
type: docs
weight: 160
url: "/net/aspose.pdf.ai/iopenaiclient/getrunsasync/"
product_version: "26.9.0"
---
## IOpenAIClient.GetRunsAsync method

Retrieves a list of runs for a specified thread asynchronously.

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | The ID of the thread to retrieve runs from. |
| queryParameters | RunListQueryParameters | Optional query parameters to filter the list of runs. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains a list of runs.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the thread Id is null or empty. |

### See Also

* class [RunListQueryParameters](../../../aspose.pdf.ai/runlistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

