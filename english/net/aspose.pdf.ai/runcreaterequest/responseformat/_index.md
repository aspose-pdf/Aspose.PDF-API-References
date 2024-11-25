---
title: RunCreateRequest.ResponseFormat
second_title: Aspose.PDF for .NET API Reference
description: RunCreateRequest property. Gets or sets the response format. Specifies the format that the model must output. Compatible with GPT4o GPT4 Turbo and all GPT3.5 Turbo models since gpt3.5turbo1106. Setting to  type json_object  enables JSON mode which guarantees the message the model generates is valid JSON. Important when using JSON mode you must also instruct the model to produce JSON yourself via a system or user message. Without this the model may generate an unending stream of whitespace until the generation reaches the token limit resulting in a longrunning and seemingly stuck request. Also note that the message content may be partially cut off if finish_reasonlength which indicates the generation exceeded max_tokens or the conversation exceeded the max context length
type: docs
weight: 100
url: /net/aspose.pdf.ai/runcreaterequest/responseformat/
---
## RunCreateRequest.ResponseFormat property

Gets or sets the response format. Specifies the format that the model must output. Compatible with GPT-4o, GPT-4 Turbo, and all GPT-3.5 Turbo models since gpt-3.5-turbo-1106. Setting to { "type": "json_object" } enables JSON mode, which guarantees the message the model generates is valid JSON. Important: when using JSON mode, you must also instruct the model to produce JSON yourself via a system or user message. Without this, the model may generate an unending stream of whitespace until the generation reaches the token limit, resulting in a long-running and seemingly "stuck" request. Also note that the message content may be partially cut off if finish_reason="length", which indicates the generation exceeded max_tokens or the conversation exceeded the max context length.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### See Also

* class [ResponseFormat](../../responseformat/)
* class [RunCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


