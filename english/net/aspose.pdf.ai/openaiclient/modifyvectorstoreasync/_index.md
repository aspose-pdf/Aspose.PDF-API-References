---
title: "OpenAIClient.ModifyVectorStoreAsync"
linktitle: "ModifyVectorStoreAsync"
articleTitle: "ModifyVectorStoreAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "OpenAIClient method. Modifies an existing vector store asynchronously."
type: docs
weight: 130
url: "/net/aspose.pdf.ai/openaiclient/modifyvectorstoreasync/"
product_version: "26.9.0"
---
## OpenAIClient.ModifyVectorStoreAsync method

Modifies an existing vector store asynchronously.

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | The ID of the vector store to modify. |
| vectorStoreModifyRequest | VectorStoreModifyRequest | The request object containing modification details. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the response from the vector store modification.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the vector store Id is null or empty. |

### See Also

* class [VectorStoreModifyRequest](../../../aspose.pdf.ai/vectorstoremodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

