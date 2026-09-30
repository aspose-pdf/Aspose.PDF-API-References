---
title: "FileResponse Class"
linktitle: "FileResponse"
articleTitle: "FileResponse"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.FileResponse class. The FileResponse object represents a document that has been uploaded to OpenAI."
type: docs
weight: 420
url: "/net/aspose.pdf.ai/fileresponse/"
keywords: "FileResponse, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## FileResponse class

The FileResponse object represents a document that has been uploaded to OpenAI.

```csharp
public class FileResponse : BaseResponse, IEntityId
```

## Constructors

| Name | Description |
| --- | --- |
| [FileResponse](./fileresponse/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Bytes](./bytes/) { get; set; } | Gets or sets the size of the file, in bytes. |
| [CreatedAt](./createdat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the file was created. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Gets or sets the response detail. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Gets or sets the HTTP response error. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Gets or sets the error information. |
| [Filename](./filename/) { get; set; } | Gets or sets the name of the file. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Gets or sets the HTTP response headers. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Gets or sets the HTTP status code. |
| [Id](./id/) { get; set; } | Gets or sets the file identifier, which can be referenced in the API endpoints. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indicates if the response was successful. |
| [Object](./object/) { get; set; } | Gets or sets the object type, which is always file. |
| [Purpose](./purpose/) { get; set; } | Gets or sets the intended purpose of the file. Supported values are assistants, assistants_output, batch, batch_output, fine-tune, fine-tune-results and vision. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Gets the error reason phrase. |

### See Also

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

