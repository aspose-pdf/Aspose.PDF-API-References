---
title: Interface IChatCopilot
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.IChatCopilot interface. Represents a chat copilot for interacting with documents via AI models
type: docs
weight: 470
url: /net/aspose.pdf.ai/ichatcopilot/
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
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) | Asynchronously gets a response for the given list of messages. |
| [GetResponseAsync](../../aspose.pdf.ai/ichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) | Asynchronously gets a response for the given message. |
| [SaveContextAsync](../../aspose.pdf.ai/ichatcopilot/savecontextasync/)(string, CancellationToken?) | Asynchronously saves the context to a JSON file. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) | Asynchronously saves the responses for the given list of messages to a PDF file. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) | Asynchronously saves the response for the given message to a PDF file. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) | Asynchronously saves the responses for the given list of messages to a file with specified format. |
| [SaveResponseAsync](../../aspose.pdf.ai/ichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) | Asynchronously saves the response for the given message to a file with specified format. |

### See Also

* interface [IAICopilot](../iaicopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


