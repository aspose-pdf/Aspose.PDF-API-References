---
title: Class VectorStoreResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreResponse class. The vector store object
type: docs
weight: 1480
url: /net/aspose.pdf.ai/vectorstoreresponse/
---
## VectorStoreResponse class

The vector store object.

```csharp
public class VectorStoreResponse : BaseResponse, IEntityId, IStatus
```

## Constructors

| Name | Description |
| --- | --- |
| [VectorStoreResponse](vectorstoreresponse/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstoreresponse/createdat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the vector store was created. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Gets or sets the response detail. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Gets or sets the HTTP response error. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Gets or sets the error information. |
| [ExpiresAfter](../../aspose.pdf.ai/vectorstoreresponse/expiresafter/) { get; set; } | Gets or sets the expiration policy for a vector store. |
| [ExpiresAt](../../aspose.pdf.ai/vectorstoreresponse/expiresat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the vector store will expire. |
| [FileCounts](../../aspose.pdf.ai/vectorstoreresponse/filecounts/) { get; set; } | Gets or sets the number of files that have been processed. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Gets or sets the HTTP response headers. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Gets or sets the HTTP status code. |
| [Id](../../aspose.pdf.ai/vectorstoreresponse/id/) { get; set; } | Gets or sets the identifier, which can be referenced in API endpoints. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indicates if the response was successful. |
| [LastActiveAt](../../aspose.pdf.ai/vectorstoreresponse/lastactiveat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the vector store was last active. |
| [Metadata](../../aspose.pdf.ai/vectorstoreresponse/metadata/) { get; set; } | Gets or sets s set of 16 key-value pairs that can be attached to an object. This can be useful for storing additional information about the object in a structured format. Keys can be a maximum of 64 characters long and values can be a maximum of 512 characters long. |
| [Name](../../aspose.pdf.ai/vectorstoreresponse/name/) { get; set; } | Gets or sets the name of the vector store. |
| [Object](../../aspose.pdf.ai/vectorstoreresponse/object/) { get; set; } | Gets or sets the object type, which is always vector_store. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Gets the error reason phrase. |
| [Status](../../aspose.pdf.ai/vectorstoreresponse/status/) { get; set; } | Gets or sets the status of the vector store, which can be either expired, in_progress, or completed. A status of completed indicates that the vector store is ready for use. |
| [UsageBytes](../../aspose.pdf.ai/vectorstoreresponse/usagebytes/) { get; set; } | Gets or sets the total number of bytes used by the files in the vector store. |

### See Also

* class [BaseResponse](../baseresponse/)
* interface [IEntityId](../ientityid/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


