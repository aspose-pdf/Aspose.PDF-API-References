---
title: "IChatCopilot Interface"
linktitle: "IChatCopilot"
articleTitle: "IChatCopilot"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.IChatCopilot interface. Represents a chat copilot for interacting with documents via AI models."
type: docs
weight: 490
url: "/net/aspose.pdf.ai/ichatcopilot/"
product_version: "26.9"
---
## IChatCopilot interface

Represents a chat copilot for interacting with documents via AI models.

```csharp
public interface IChatCopilot : IAICopilot
```

## Methods

| Name | Description |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/ichatcopilot/deletecontextasync/)(CancellationToken?) | Asynchronously deletes the context. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/)(string, CancellationToken?) | Asynchronously gets a response for the given message. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/)(List&lt;string&gt;, CancellationToken?) | Asynchronously gets a response for the given list of messages. |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | Asynchronously saves the context to a JSON file. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/)(string, string, CancellationToken?) | Asynchronously saves the response for the given message to a PDF file. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/)(string, string, SaveFormat, CancellationToken?) | Asynchronously saves the response for the given message to a file with specified format. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/)(List&lt;string&gt;, string, CancellationToken?) | Asynchronously saves the responses for the given list of messages to a PDF file. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) | Asynchronously saves the responses for the given list of messages to a file with specified format. |

### See Also

* interface [IAICopilot](../iaicopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

