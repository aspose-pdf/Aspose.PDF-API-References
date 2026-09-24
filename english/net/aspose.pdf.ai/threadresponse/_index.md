---
title: "ThreadResponse Class"
linktitle: "ThreadResponse"
articleTitle: "ThreadResponse"
second_title: "Aspose.PDF for .NET"
description: "Represents a thread that contains messages."
type: docs
weight: 1270
url: "/net/aspose.pdf.ai/threadresponse/"
keywords: "ThreadResponse, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## ThreadResponse class

Represents a thread that contains messages.

```csharp
public class ThreadResponse : BaseResponse
```

## Constructors

| Name | Description |
| --- | --- |
| [ThreadResponse](./threadresponse/#constructor) | Initializes a new instance of the ThreadResponse class. |

## Properties

| Name | Description |
| --- | --- |
| [CreatedAt](./createdat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the thread was created. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Gets or sets the response detail. *(Inherited from BaseResponse)* |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Gets or sets the HTTP response error. *(Inherited from BaseResponse)* |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Gets or sets the error information. *(Inherited from BaseResponse)* |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Gets or sets the HTTP response headers. *(Inherited from BaseResponse)* |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Gets or sets the HTTP status code. *(Inherited from BaseResponse)* |
| [Id](./id/) { get; set; } | Gets or sets the identifier, which can be referenced in API endpoints. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indicates if the response was successful. *(Inherited from BaseResponse)* |
| [Metadata](./metadata/) { get; set; } | Gets or sets a set of 16 key-value pairs that can be attached to an object. This can be useful for storing. |
| [Object](./object/) { get; set; } | Gets or sets the object type, which is always thread. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Gets the error reason phrase. *(Inherited from BaseResponse)* |
| [ToolResources](./toolresources/) { get; set; } | Gets or sets a set of resources that are made available to the assistant's tools in this thread. The resources are. |

### See Also

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

