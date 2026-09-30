---
title: "VectorStoreResponse Class"
linktitle: "VectorStoreResponse"
articleTitle: "VectorStoreResponse"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.VectorStoreResponse class. The vector store object."
type: docs
weight: 1480
url: "/net/aspose.pdf.ai/vectorstoreresponse/"
keywords: "VectorStoreResponse, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## VectorStoreResponse class

The vector store object.

```csharp
public class VectorStoreResponse : BaseResponse, IEntityId, IStatus
```

## Constructors

| Name | Description |
| --- | --- |
| [VectorStoreResponse](./vectorstoreresponse/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [CreatedAt](./createdat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the vector store was created. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Gets or sets the response detail. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Gets or sets the HTTP response error. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Gets or sets the error information. |
| [ExpiresAfter](./expiresafter/) { get; set; } | Gets or sets the expiration policy for a vector store. |
| [ExpiresAt](./expiresat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the vector store will expire. |
| [FileCounts](./filecounts/) { get; set; } | Gets or sets the number of files that have been processed. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Gets or sets the HTTP response headers. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Gets or sets the HTTP status code. |
| [Id](./id/) { get; set; } | Gets or sets the identifier, which can be referenced in API endpoints. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indicates if the response was successful. |
| [LastActiveAt](./lastactiveat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the vector store was last active. |
| [Metadata](./metadata/) { get; set; } | Gets or sets s set of 16 key-value pairs that can be attached to an object. This can be useful for storing additional information about the object in a structured format. Keys can be a maximum of 64 characters long and values can be a maximum of 512 characters long. |
| [Name](./name/) { get; set; } | Gets or sets the name of the vector store. |
| [Object](./object/) { get; set; } | Gets or sets the object type, which is always vector_store. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Gets the error reason phrase. |
| [Status](./status/) { get; set; } | Gets or sets the status of the vector store, which can be either expired, in_progress, or completed. A status of completed indicates that the vector store is ready for use. |
| [UsageBytes](./usagebytes/) { get; set; } | Gets or sets the total number of bytes used by the files in the vector store. |

### See Also

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

