---
title: Class LlamaChatCompletionResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.LlamaChatCompletionResponse class. Represents a chat completion response returned by model based on the provided input
type: docs
weight: 740
url: /net/aspose.pdf.ai/llamachatcompletionresponse/
---
## LlamaChatCompletionResponse class

Represents a chat completion response returned by model, based on the provided input.

```csharp
public class LlamaChatCompletionResponse : BaseResponse
```

## Constructors

| Name | Description |
| --- | --- |
| [LlamaChatCompletionResponse](llamachatcompletionresponse/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Choices](../../aspose.pdf.ai/llamachatcompletionresponse/choices/) { get; set; } | Gets or sets a list of chat completion choices. Can be more than one if n is greater than 1. |
| [Created](../../aspose.pdf.ai/llamachatcompletionresponse/created/) { get; set; } | Gets or sets the Unix timestamp (in seconds) of when the chat completion was created. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Gets or sets the response detail. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Gets or sets the HTTP response error. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Gets or sets the error information. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Gets or sets the HTTP response headers. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Gets or sets the HTTP status code. |
| [Id](../../aspose.pdf.ai/llamachatcompletionresponse/id/) { get; set; } | Gets or sets a unique identifier for the chat completion. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indicates if the response was successful. |
| [Model](../../aspose.pdf.ai/llamachatcompletionresponse/model/) { get; set; } | Gets or sets the model used for the chat completion. |
| [Object](../../aspose.pdf.ai/llamachatcompletionresponse/object/) { get; set; } | Gets or sets the object type, which is always chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Gets the error reason phrase. |
| [SystemFingerprint](../../aspose.pdf.ai/llamachatcompletionresponse/systemfingerprint/) { get; set; } | Gets or sets the fingerprint that represents the backend configuration that the model runs with. |
| [Usage](../../aspose.pdf.ai/llamachatcompletionresponse/usage/) { get; set; } | Gets or sets usage statistics for the completion request. |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/llamachatcompletionresponse/tostring/)() | Returns a string representation of the first choice. |

### See Also

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


