---
title: "OpenAIClient.CreateVectorStoreFileAsync"
linktitle: "CreateVectorStoreFileAsync"
articleTitle: "CreateVectorStoreFileAsync"
second_title: "Aspose.PDF for .NET"
description: "Creates a new vector store file asynchronously."
type: docs
weight: 50
url: "/net/aspose.pdf.ai/openaiclient/createvectorstorefileasync/"
product_version: "26.9.0"
---
## CreateVectorStoreFileAsync(string, [VectorStoreFileCreateRequest](../../../aspose.pdf.ai/vectorstorefilecreaterequest/), Nullable<CancellationToken>) {#createvectorstorefileasync}

Creates a new vector store file asynchronously.

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, VectorStoreFileCreateRequest vectorStoreFileCreateRequest, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| vectorStoreId | string | The ID of the vector store where the file will be created. |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | The request object containing details for creating the file. |
| cancellationToken | Nullable<CancellationToken> | A token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[VectorStoreFileResponse](../../../aspose.pdf.ai/vectorstorefileresponse/)>

A task that represents the asynchronous operation. The task result contains the response from the file creation.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../../aspose.pdf.ai/aiclientexception/) | Thrown when the vector store Id is null or empty. |

### See Also

* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

