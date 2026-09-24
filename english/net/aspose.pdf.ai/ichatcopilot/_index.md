---
title: "IChatCopilot Interface"
linktitle: "IChatCopilot"
articleTitle: "IChatCopilot"
second_title: "Aspose.PDF for .NET"
description: "Represents a chat copilot for interacting with documents via AI models."
type: docs
weight: 490
url: "/net/aspose.pdf.ai/ichatcopilot/"
product_version: "26.9.0"
---
## IChatCopilot interface

Represents a chat copilot for interacting with documents via AI models.

```csharp
public interface IChatCopilot
```

## Methods

| Name | Description |
| --- | --- |
| [DeleteContextAsync](./deletecontextasync/)(*Nullable<CancellationToken>*) | Asynchronously deletes the context. |
| [GetResponseAsync](./getresponseasync/)(*string, Nullable<CancellationToken>*) | Asynchronously gets a response for the given message. |
| [GetResponseAsync](./getresponseasync/)(*List<string>, Nullable<CancellationToken>*) | Asynchronously gets a response for the given list of messages. |
| [SaveContextAsync](./savecontextasync/)(*string, Nullable<CancellationToken>*) | Asynchronously saves the context to a JSON file. |
| [SaveResponseAsync](./saveresponseasync/)(*string, string, Nullable<CancellationToken>*) | Asynchronously saves the response for the given message to a PDF file. |
| [SaveResponseAsync](./saveresponseasync/)(*List<string>, string, Nullable<CancellationToken>*) | Asynchronously saves the responses for the given list of messages to a PDF file. |
| [SaveResponseAsync](./saveresponseasync/)(*string, string, SaveFormat, Nullable<CancellationToken>*) | Asynchronously saves the response for the given message to a file with specified format. |
| [SaveResponseAsync](./saveresponseasync/)(*List<string>, string, SaveFormat, Nullable<CancellationToken>*) | Asynchronously saves the responses for the given list of messages to a file with specified format. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

