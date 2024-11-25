---
title: Class VectorStoreFileResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.VectorStoreFileResponse class. A vector store file response
type: docs
weight: 1350
url: /net/aspose.pdf.ai/vectorstorefileresponse/
---
## VectorStoreFileResponse class

A vector store file response.

```csharp
public class VectorStoreFileResponse : BaseResponse, IStatus
```

## Constructors

| Name | Description |
| --- | --- |
| [VectorStoreFileResponse](vectorstorefileresponse/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/vectorstorefileresponse/createdat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the vector store file was created. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Gets or sets the response detail. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Gets or sets the HTTP response error. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Gets or sets the error information. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Gets or sets the HTTP response headers. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Gets or sets the HTTP status code. |
| [Id](../../aspose.pdf.ai/vectorstorefileresponse/id/) { get; set; } | Gets or sets the identifier, which can be referenced in API endpoints. /// |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indicates if the response was successful. |
| [LastError](../../aspose.pdf.ai/vectorstorefileresponse/lasterror/) { get; set; } | Gets or sets the last error associated with this vector store file. Will be null if there are no errors. |
| [Object](../../aspose.pdf.ai/vectorstorefileresponse/object/) { get; set; } | Gets or sets the object type, which is always vector_store.file. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Gets the error reason phrase. |
| [Status](../../aspose.pdf.ai/vectorstorefileresponse/status/) { get; set; } | Gets or sets the status of the vector store file, which can be either in_progress, completed, cancelled, or failed. The status completed indicates that the vector store file is ready for use. |
| [UsageBytes](../../aspose.pdf.ai/vectorstorefileresponse/usagebytes/) { get; set; } | Gets or sets the total vector store usage in bytes. Note that this may be different from the original file size. |
| [VectorStoreId](../../aspose.pdf.ai/vectorstorefileresponse/vectorstoreid/) { get; set; } | Gets or sets the ID of the vector store that the File is attached to. |

### See Also

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


