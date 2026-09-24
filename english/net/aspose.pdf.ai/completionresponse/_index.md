---
title: "CompletionResponse Class"
linktitle: "CompletionResponse"
articleTitle: "CompletionResponse"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.CompletionResponse class. Represents a chat completion response returned by model, based on the provided input."
type: docs
weight: 230
url: "/net/aspose.pdf.ai/completionresponse/"
keywords: "CompletionResponse, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## CompletionResponse class

Represents a chat completion response returned by model, based on the provided input.

```csharp
public class CompletionResponse : BaseResponse
```

## Constructors

| Name | Description |
| --- | --- |
| [CompletionResponse](./completionresponse/#constructor) | Initializes a new instance of the CompletionResponse class. |

## Properties

| Name | Description |
| --- | --- |
| [Choices](./choices/) { get; set; } | Gets or sets a list of chat completion choices. Can be more than one if n is greater than 1. |
| [Created](./created/) { get; set; } | Gets or sets the Unix timestamp (in seconds) of when the chat completion was created. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Gets or sets the response detail. *(Inherited from BaseResponse)* |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Gets or sets the HTTP response error. *(Inherited from BaseResponse)* |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Gets or sets the error information. *(Inherited from BaseResponse)* |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Gets or sets the HTTP response headers. *(Inherited from BaseResponse)* |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Gets or sets the HTTP status code. *(Inherited from BaseResponse)* |
| [Id](./id/) { get; set; } | Gets or sets a unique identifier for the chat completion. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indicates if the response was successful. *(Inherited from BaseResponse)* |
| [Model](./model/) { get; set; } | Gets or sets the model used for the chat completion. |
| [Object](./object/) { get; set; } | Gets or sets the object type, which is always chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Gets the error reason phrase. *(Inherited from BaseResponse)* |
| [SystemFingerprint](./systemfingerprint/) { get; set; } | Gets or sets the fingerprint that represents the backend configuration that the model runs with. |
| [Usage](./usage/) { get; set; } | Gets or sets the usage statistics for the completion request. |

## Methods

| Name | Description |
| --- | --- |
| [ToString](./tostring/) | Returns the content of the first choice as a string. |

### See Also

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

