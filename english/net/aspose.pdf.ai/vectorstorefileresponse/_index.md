---
title: "VectorStoreFileResponse Class"
linktitle: "VectorStoreFileResponse"
articleTitle: "VectorStoreFileResponse"
second_title: "Aspose.PDF for .NET"
description: "A vector store file response."
type: docs
weight: 1440
url: "/net/aspose.pdf.ai/vectorstorefileresponse/"
keywords: "VectorStoreFileResponse, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## VectorStoreFileResponse class

A vector store file response.

```csharp
public class VectorStoreFileResponse : BaseResponse, IStatus
```

## Constructors

| Name | Description |
| --- | --- |
| [VectorStoreFileResponse](./vectorstorefileresponse/#constructor) | Initializes a new instance of the VectorStoreFileResponse class. |

## Properties

| Name | Description |
| --- | --- |
| [CreatedAt](./createdat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the vector store file was created. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Gets or sets the response detail. *(Inherited from BaseResponse)* |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Gets or sets the HTTP response error. *(Inherited from BaseResponse)* |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Gets or sets the error information. *(Inherited from BaseResponse)* |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Gets or sets the HTTP response headers. *(Inherited from BaseResponse)* |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Gets or sets the HTTP status code. *(Inherited from BaseResponse)* |
| [Id](./id/) { get; set; } | Gets or sets the identifier, which can be referenced in API endpoints. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indicates if the response was successful. *(Inherited from BaseResponse)* |
| [LastError](./lasterror/) { get; set; } | Gets or sets the last error associated with this vector store file. Will be null if there are no errors. |
| [Object](./object/) { get; set; } | Gets or sets the object type, which is always vector_store.file. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Gets the error reason phrase. *(Inherited from BaseResponse)* |
| [Status](./status/) { get; set; } | Gets or sets the status of the vector store file, which can be either in_progress, completed,. |
| [UsageBytes](./usagebytes/) { get; set; } | Gets or sets the total vector store usage in bytes. Note that this may be different from the original file size. |
| [VectorStoreId](./vectorstoreid/) { get; set; } | Gets or sets the ID of the vector store that the File is attached to. |

### See Also

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

