---
title: Class ChatMessage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.ChatMessage class. A chat completion message generated by the model
type: docs
weight: 190
url: /net/aspose.pdf.ai/chatmessage/
---
## ChatMessage class

A chat completion message generated by the model.

```csharp
public class ChatMessage
```

## Constructors

| Name | Description |
| --- | --- |
| [ChatMessage](chatmessage/#constructor)() | Initializes a new instance of the `ChatMessage` class. |
| [ChatMessage](chatmessage/#constructor_1)(string, string) | Initializes a new instance of the `ChatMessage` class. |

## Properties

| Name | Description |
| --- | --- |
| [Content](../../aspose.pdf.ai/chatmessage/content/) { get; set; } | Gets or sets the contents of the message. |
| [Name](../../aspose.pdf.ai/chatmessage/name/) { get; set; } | Gets or sets an optional name for the participant. Provides the model information to differentiate between participants of the same role. |
| [Role](../../aspose.pdf.ai/chatmessage/role/) { get; set; } | Gets or sets the role of the messages author. |
| [ToolCallId](../../aspose.pdf.ai/chatmessage/toolcallid/) { get; set; } | Gets or sets tool call that this message is responding to. |
| [ToolCalls](../../aspose.pdf.ai/chatmessage/toolcalls/) { get; set; } | Gets or sets the tool calls generated by the model, such as function calls. |

## Methods

| Name | Description |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/chatmessage/fromassistant/)(string) | Creates a new ChatMessage object representing an assistant message. |
| static [FromSystem](../../aspose.pdf.ai/chatmessage/fromsystem/)(string) | Creates a new ChatMessage object representing a system message. |
| static [FromUser](../../aspose.pdf.ai/chatmessage/fromuser/)(string) | Creates a new ChatMessage object representing a user message. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


