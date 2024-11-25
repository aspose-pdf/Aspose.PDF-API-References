---
title: Class CreateChatCompletionChunkResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.CreateChatCompletionChunkResponse class. Represents a streamed chunk of a chat completion response returned by model based on the provided input
type: docs
weight: 250
url: /net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## CreateChatCompletionChunkResponse class

Represents a streamed chunk of a chat completion response returned by model, based on the provided input.

```csharp
public class CreateChatCompletionChunkResponse
```

## Constructors

| Name | Description |
| --- | --- |
| [CreateChatCompletionChunkResponse](createchatcompletionchunkresponse/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | Gets or sets a list of chat completion choices. Can contain more than one elements if n is greater than 1. Can also be empty for the last chunk if you set stream_options: {"include_usage": true}. |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | Gets or sets the Unix timestamp (in seconds) of when the chat completion was created. Each chunk has the same timestamp. |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | Gets or sets a unique identifier for the chat completion. Each chunk has the same ID. |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | Gets or sets the model to generate the completion. |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | Gets or sets the object type, which is always chat.completion.chunk. |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | Gets or sets the fingerprint that represents the backend configuration that the model runs with. Can be used in conjunction with the seed request parameter to understand when backend changes have been made that might impact determinism. |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | Gets or sets an optional field that will only be present when you set stream_options: {"include_usage": true} in your request. When present, it contains a null value except for the last chunk which contains the token usage statistics for the entire request. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


