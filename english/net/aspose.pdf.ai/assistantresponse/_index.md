---
title: Class AssistantResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.AssistantResponse class. Represents an assistant that can call the model and use tools
type: docs
weight: 140
url: /net/aspose.pdf.ai/assistantresponse/
---
## AssistantResponse class

Represents an assistant that can call the model and use tools.

```csharp
public class AssistantResponse : BaseResponse
```

## Constructors

| Name | Description |
| --- | --- |
| [AssistantResponse](assistantresponse/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/assistantresponse/createdat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the assistant was created. |
| [Description](../../aspose.pdf.ai/assistantresponse/description/) { get; set; } | Gets or sets the description of the assistant. The maximum length is 512 characters. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Gets or sets the response detail. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Gets or sets the HTTP response error. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Gets or sets the error information. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Gets or sets the HTTP response headers. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Gets or sets the HTTP status code. |
| [Id](../../aspose.pdf.ai/assistantresponse/id/) { get; set; } | Gets or sets the identifier, which can be referenced in API endpoints. |
| [Instructions](../../aspose.pdf.ai/assistantresponse/instructions/) { get; set; } | Gets or sets the system instructions that the assistant uses. The maximum length is 256,000 characters. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indicates if the response was successful. |
| [Metadata](../../aspose.pdf.ai/assistantresponse/metadata/) { get; set; } | Gets or sets a set of 16 key-value pairs that can be attached to an object. This can be useful for storing additional information about the object in a structured format. Keys can be a maximum of 64 characters long and values can be a maximum of 512 characters long. |
| [Model](../../aspose.pdf.ai/assistantresponse/model/) { get; set; } | Gets or sets the ID of the model to use. You can use the List models API to see all of your available models, or see our Model overview for descriptions of them. |
| [Name](../../aspose.pdf.ai/assistantresponse/name/) { get; set; } | Gets or sets the name of the assistant. The maximum length is 256 characters. |
| [Object](../../aspose.pdf.ai/assistantresponse/object/) { get; set; } | Gets or sets the object type, which is always assistant. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Gets the error reason phrase. |
| [ResponseFormat](../../aspose.pdf.ai/assistantresponse/responseformat/) { get; set; } | Gets or sets the format that the model must output. Compatible with GPT-4o, GPT-4 Turbo, and all GPT-3.5 Turbo models since gpt-3.5-turbo-1106 . Setting to { "type": "json_object" } enables JSON mode, which guarantees the message the model generates is valid JSON. Important: when using JSON mode, you must also instruct the model to produce JSON yourself via a system or user message. Without this, the model may generate an unending stream of whitespace until the generation reaches the token limit, resulting in a long-running and seemingly "stuck" request. Also note that the message content may be partially cut off if finish_reason="length", which indicates the generation exceeded max_tokens or the conversation exceeded the max context length. |
| [Temperature](../../aspose.pdf.ai/assistantresponse/temperature/) { get; set; } | Gets or sets what sampling temperature to use, between 0 and 2. Higher values like 0.8 will make the output more random, while lower values like 0.2 will make it more focused and deterministic. |
| [ToolResources](../../aspose.pdf.ai/assistantresponse/toolresources/) { get; set; } | Gets or sets a set of resources that are used by the assistant's tools. The resources are specific to the type of tool. For example, the code_interpreter tool requires a list of file IDs, while the file_search tool requires a list of vector store IDs. |
| [Tools](../../aspose.pdf.ai/assistantresponse/tools/) { get; set; } | Gets or sets a list of tool enabled on the assistant. There can be a maximum of 128 tools per assistant. Tools can be of types code_interpreter, file_search, or function. |
| [TopP](../../aspose.pdf.ai/assistantresponse/topp/) { get; set; } | Gets or sets an alternative to sampling with temperature, called nucleus sampling, where the model considers the results of the tokens with top_p probability mass. So 0.1 means only the tokens comprising the top 10% probability mass are considered. We generally recommend altering this or temperature but not both. |

### See Also

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


