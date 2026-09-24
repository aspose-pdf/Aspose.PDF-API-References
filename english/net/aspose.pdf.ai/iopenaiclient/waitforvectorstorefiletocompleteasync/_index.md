---
title: "IOpenAIClient.WaitForVectorStoreFileToCompleteAsync"
linktitle: "WaitForVectorStoreFileToCompleteAsync"
articleTitle: "WaitForVectorStoreFileToCompleteAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Waits for a specific vector store file to complete asynchronously."
type: docs
weight: 50
url: "/net/aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync/"
product_version: "26.9.0"
---
## WaitForVectorStoreFileToCompleteAsync(string, string, Nullable<CancellationToken>) {#waitforvectorstorefiletocompleteasync}

Waits for a specific vector store file to complete asynchronously.

```csharp
public Task<VectorStoreFileResponse> WaitForVectorStoreFileToCompleteAsync(string vectorStoreId, string fileId, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | string | The ID of the vector store containing the file. |
| fileId | string | The ID of the file to monitor until completion. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[VectorStoreFileResponse](../../../aspose.pdf.ai/vectorstorefileresponse/)>

A task that represents the asynchronous operation. The task result contains the final status of the file.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the vector store Id is null or empty. |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the file Id is null or empty. |

### See Also

* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

