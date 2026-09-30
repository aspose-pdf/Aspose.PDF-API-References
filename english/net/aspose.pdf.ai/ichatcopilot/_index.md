---
title: "IChatCopilot Interface"
linktitle: "IChatCopilot"
articleTitle: "IChatCopilot"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.IChatCopilot interface. Represents a chat copilot for interacting with documents via AI models."
type: docs
weight: 490
url: "/net/aspose.pdf.ai/ichatcopilot/"
product_version: "26.9.0"
---
## IChatCopilot interface

Represents a chat copilot for interacting with documents via AI models.

```csharp
public interface IChatCopilot : IAICopilot
```

## Methods

| Name | Description |
| --- | --- |
| [DeleteContextAsync](./deletecontextasync/)(CancellationToken?) | Asynchronously deletes the context. |
| [GetResponseAsync](./getresponseasync/)(List<string>, CancellationToken?) | Asynchronously gets a response for the given list of messages. |
| [GetResponseAsync](./getresponseasync/)(string, CancellationToken?) | Asynchronously gets a response for the given message. |
| [SaveContextAsync](./savecontextasync/)(string, CancellationToken?) | Asynchronously saves the context to a JSON file. |
| [SaveResponseAsync](./saveresponseasync/)(List<string>, string, CancellationToken?) | Asynchronously saves the responses for the given list of messages to a PDF file. |
| [SaveResponseAsync](./saveresponseasync/)(string, string, CancellationToken?) | Asynchronously saves the response for the given message to a PDF file. |
| [SaveResponseAsync](./saveresponseasync/)(List<string>, string, SaveFormat, CancellationToken?) | Asynchronously saves the responses for the given list of messages to a file with specified format. |
| [SaveResponseAsync](./saveresponseasync/)(string, string, SaveFormat, CancellationToken?) | Asynchronously saves the response for the given message to a file with specified format. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

