---
title: "IOpenAIClient.WaitForVectorStoreToCompleteAsync"
linktitle: "WaitForVectorStoreToCompleteAsync"
articleTitle: "WaitForVectorStoreToCompleteAsync"
second_title: "Aspose.PDF for .NET"
description: "Waits for a specific vector store to complete asynchronously."
type: docs
weight: 400
url: "/net/aspose.pdf.ai/iopenaiclient/waitforvectorstoretocompleteasync/"
product_version: "26.9.0"
---
## WaitForVectorStoreToCompleteAsync(string, Nullable<CancellationToken>) {#waitforvectorstoretocompleteasync}

Waits for a specific vector store to complete asynchronously.

```csharp
public Task<VectorStoreResponse> WaitForVectorStoreToCompleteAsync(string vectorStoreId, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | string | The ID of the vector store to monitor until completion. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[VectorStoreResponse](../../../aspose.pdf.ai/vectorstoreresponse/)>

A task that represents the asynchronous operation. The task result contains the final status of the vector store.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the vector store Id is null or empty. |

### See Also

* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

