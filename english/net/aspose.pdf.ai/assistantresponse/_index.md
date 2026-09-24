---
title: "AssistantResponse Class"
linktitle: "AssistantResponse"
articleTitle: "AssistantResponse"
second_title: "Aspose.PDF for .NET"
description: "Represents an assistant that can call the model and use tools."
type: docs
weight: 110
url: "/net/aspose.pdf.ai/assistantresponse/"
keywords: "AssistantResponse, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## AssistantResponse class

Represents an assistant that can call the model and use tools.

```csharp
public class AssistantResponse : BaseResponse
```

## Constructors

| Name | Description |
| --- | --- |
| [AssistantResponse](./assistantresponse/#constructor) | Initializes a new instance of the AssistantResponse class. |

## Properties

| Name | Description |
| --- | --- |
| [CreatedAt](./createdat/) { get; set; } | Gets or sets the Unix timestamp (in seconds) for when the assistant was created. |
| [Description](./description/) { get; set; } | Gets or sets the description of the assistant. The maximum length is 512 characters. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Gets or sets the response detail. *(Inherited from BaseResponse)* |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Gets or sets the HTTP response error. *(Inherited from BaseResponse)* |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Gets or sets the error information. *(Inherited from BaseResponse)* |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Gets or sets the HTTP response headers. *(Inherited from BaseResponse)* |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Gets or sets the HTTP status code. *(Inherited from BaseResponse)* |
| [Id](./id/) { get; set; } | Gets or sets the identifier, which can be referenced in API endpoints. |
| [Instructions](./instructions/) { get; set; } | Gets or sets the system instructions that the assistant uses. The maximum length is 256,000. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indicates if the response was successful. *(Inherited from BaseResponse)* |
| [Metadata](./metadata/) { get; set; } | Gets or sets a set of 16 key-value pairs that can be attached to an object. This can be useful for storing. |
| [Model](./model/) { get; set; } | Gets or sets the ID of the model to use. You can use the List models API to see all of your available. |
| [Name](./name/) { get; set; } | Gets or sets the name of the assistant. The maximum length is 256 characters. |
| [Object](./object/) { get; set; } | Gets or sets the object type, which is always assistant. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Gets the error reason phrase. *(Inherited from BaseResponse)* |
| [ResponseFormat](./responseformat/) { get; set; } | Gets or sets the format that the model must output. Compatible with GPT-4o, GPT-4 Turbo,. |
| [Temperature](./temperature/) { get; set; } | Gets or sets what sampling temperature to use, between 0 and 2. Higher values like 0.8 will make the. |
| [ToolResources](./toolresources/) { get; set; } | Gets or sets a set of resources that are used by the assistant's tools. The resources are specific to. |
| [Tools](./tools/) { get; set; } | Gets or sets a list of tool enabled on the assistant. There can be a maximum of 128 tools per. |
| [TopP](./topp/) { get; set; } | Gets or sets an alternative to sampling with temperature, called nucleus sampling, where the model. |

### See Also

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

