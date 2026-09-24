---
title: "IOpenAIClient.ModifyVectorStoreAsync"
linktitle: "ModifyVectorStoreAsync"
articleTitle: "ModifyVectorStoreAsync"
second_title: "Aspose.PDF for .NET"
description: "Modifies an existing vector store asynchronously."
type: docs
weight: 380
url: "/net/aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/"
product_version: "26.9.0"
---
## ModifyVectorStoreAsync(string, [VectorStoreModifyRequest](../../../aspose.pdf.ai/vectorstoremodifyrequest/), Nullable<CancellationToken>) {#modifyvectorstoreasync}

Modifies an existing vector store asynchronously.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, VectorStoreModifyRequest vectorStoreModifyRequest, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | string | The ID of the vector store to modify. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | The request object containing modification details. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[VectorStoreResponse](../../../aspose.pdf.ai/vectorstoreresponse/)>

A task that represents the asynchronous operation. The task result contains the response from the vector store modification.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the vector store Id is null or empty. |

### See Also

* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

