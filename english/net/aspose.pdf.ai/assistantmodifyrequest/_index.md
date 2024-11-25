---
title: Class AssistantModifyRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.AssistantModifyRequest class. Request object for modifying an assistant
type: docs
weight: 130
url: /net/aspose.pdf.ai/assistantmodifyrequest/
---
## AssistantModifyRequest class

Request object for modifying an assistant.

```csharp
public class AssistantModifyRequest : AssistantCreateRequest
```

## Constructors

| Name | Description |
| --- | --- |
| [AssistantModifyRequest](assistantmodifyrequest/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Description](../../aspose.pdf.ai/assistantcreaterequest/description/) { get; set; } | Gets or sets the description of the assistant. The maximum length is 512 characters. |
| [Instructions](../../aspose.pdf.ai/assistantcreaterequest/instructions/) { get; set; } | Gets or sets the system instructions that the assistant uses. The maximum length is 256,000 characters. |
| [Metadata](../../aspose.pdf.ai/assistantcreaterequest/metadata/) { get; set; } | Gets or sets a set of 16 key-value pairs that can be attached to an object. This can be useful for storing additional information about the object in a structured format. Keys can be a maximum of 64 characters long and values can be a maximum of 512 characters long. |
| [Model](../../aspose.pdf.ai/assistantcreaterequest/model/) { get; set; } | Gets or sets ID of the model to use. You can use the List models API to see all of your available models, or see our Model overview for descriptions of them. |
| [Name](../../aspose.pdf.ai/assistantcreaterequest/name/) { get; set; } | Gets or sets the name of the assistant. The maximum length is 256 characters. |
| [ResponseFormat](../../aspose.pdf.ai/assistantcreaterequest/responseformat/) { get; set; } | Gets or sets the format that the model must output. Compatible with GPT-4o, GPT-4 Turbo, and all GPT-3.5 Turbo models since gpt-3.5-turbo-1106 . Setting to { "type": "json_object" } enables JSON mode, which guarantees the message the model generates is valid JSON. Important: when using JSON mode, you must also instruct the model to produce JSON yourself via a system or user message. Without this, the model may generate an unending stream of whitespace until the generation reaches the token limit, resulting in a long-running and seemingly "stuck" request. Also note that the message content may be partially cut off if finish_reason="length", which indicates the generation exceeded max_tokens or the conversation exceeded the max context length. |
| [Temperature](../../aspose.pdf.ai/assistantcreaterequest/temperature/) { get; set; } | Gets or sets sampling temperature to use, between 0 and 2. Higher values like 0.8 will make the output more random, while lower values like 0.2 will make it more focused and deterministic. |
| [ToolResources](../../aspose.pdf.ai/assistantcreaterequest/toolresources/) { get; set; } | Gets or sets resources that are used by the assistant's tools. The resources are specific to the type of tool. For example, the code_interpreter tool requires a list of file IDs, while the file_search tool requires a list of vector store IDs. |
| [Tools](../../aspose.pdf.ai/assistantcreaterequest/tools/) { get; set; } | Gets or sets a list of tool enabled on the assistant. There can be a maximum of 128 tools per assistant. Tools can be of types code_interpreter, file_search, or function. |
| [TopP](../../aspose.pdf.ai/assistantcreaterequest/topp/) { get; set; } | Gets or sets an alternative to sampling with temperature, called nucleus sampling, where the model considers the results of the tokens with top_p probability mass. So 0.1 means only the tokens comprising the top 10% probability mass are considered. We generally recommend altering this or temperature but not both. |

### See Also

* class [AssistantCreateRequest](../assistantcreaterequest/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


