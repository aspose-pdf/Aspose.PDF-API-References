---
title: "IOpenAIClient.CreateVectorStoreFileAsync"
linktitle: "CreateVectorStoreFileAsync"
articleTitle: "CreateVectorStoreFileAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOpenAIClient method. Creates a new vector store file asynchronously."
type: docs
weight: 10
url: "/net/aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/"
product_version: "26.9"
---
## IOpenAIClient.CreateVectorStoreFileAsync method

Creates a new vector store file asynchronously.

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | String | The ID of the vector store where the file will be created. |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | The request object containing details for creating the file. |
| cancellationToken | Nullable`1 | A token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains the response from the file creation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Thrown when the vector store Id is null or empty. |

### See Also

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* class [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

