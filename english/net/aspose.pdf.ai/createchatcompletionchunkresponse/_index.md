---
title: "CreateChatCompletionChunkResponse Class"
linktitle: "CreateChatCompletionChunkResponse"
articleTitle: "CreateChatCompletionChunkResponse"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.CreateChatCompletionChunkResponse class. Represents a streamed chunk of a chat completion response returned by model, based on the provided input."
type: docs
weight: 240
url: "/net/aspose.pdf.ai/createchatcompletionchunkresponse/"
keywords: "CreateChatCompletionChunkResponse, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## CreateChatCompletionChunkResponse class

Represents a streamed chunk of a chat completion response returned by model, based on the provided input.

```csharp
public class CreateChatCompletionChunkResponse
```

## Constructors

| Name | Description |
| --- | --- |
| [CreateChatCompletionChunkResponse](./createchatcompletionchunkresponse/#constructor) | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Choices](./choices/) { get; set; } | Gets or sets a list of chat completion choices. Can contain more than one elements if n is greater than 1. |
| [Created](./created/) { get; set; } | Gets or sets the Unix timestamp (in seconds) of when the chat completion was created. Each chunk has the same timestamp. |
| [Id](./id/) { get; set; } | Gets or sets a unique identifier for the chat completion. Each chunk has the same ID. |
| [Model](./model/) { get; set; } | Gets or sets the model to generate the completion. |
| [Object](./object/) { get; set; } | Gets or sets the object type, which is always chat.completion.chunk. |
| [SystemFingerprint](./systemfingerprint/) { get; set; } | Gets or sets the fingerprint that represents the backend configuration that the model runs with. |
| [Usage](./usage/) { get; set; } | Gets or sets an optional field that will only be present when you set stream_options: {"include_usage": true} in your request. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

