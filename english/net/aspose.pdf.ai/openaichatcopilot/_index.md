---
title: "OpenAIChatCopilot Class"
linktitle: "OpenAIChatCopilot"
articleTitle: "OpenAIChatCopilot"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.OpenAIChatCopilot class. Represents a chat copilot for interacting with documents via AI models. Example usage of creating an OpenAI client, co..."
type: docs
weight: 880
url: "/net/aspose.pdf.ai/openaichatcopilot/"
keywords: "OpenAIChatCopilot, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## OpenAIChatCopilot class

Represents a chat copilot for interacting with documents via AI models.
 
 Example usage of creating an OpenAI client, configuring options, and using the ChatCopilot to interact with user queries
 and manage conversation context.
 
 
 // Create AI client.
 var openAiClient = [OpenAIClient](../openaiclient/)
 .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
 .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
 .WithOrganization("org_123")
 .Build(); // Build.
 
 // Create copilot options.
 var options = [OpenAIChatCopilotOptions](../openaichatcopilotoptions/)
 .Create() // Create options like this, or...
 //.Create(options =&gt; { options.Model = [OpenAIModels](../openaimodels/).Gpt35Turbo; }) // ...create using delegate.
 .WithModel([OpenAIModels](../openaimodels/).Gpt35Turbo) // Configure other optional parameters.
 .WithTemperature(0.5)
 .WithTopP(1)
 .WithDocument("DocumentInputPath") // Attach documents using .WithDocument(s) methods allows to add text, pdf and paths to documents.
 .WithContextBackupJsonPath("PathToContextBackup") // Supply context backup to resume the conversation session.
 .WithRestoreContextFromBackup(true); // If set to true, the context 
 
 // Create summary copilot.
 var chatCopilot = [AICopilotFactory](../aicopilotfactory/).CreateChatCopilot(openAiClient, options);
 
 // Get response on a user query.
 string copilotResponse1 = await chatCopilot.GetResponseAsync("user message");
 
 // Get response on a list of queries.
 string copilotResponse2 = await chatCopilot.GetResponseAsync(new List&lt;string&gt;
 {
 "message1",
 "message2"
 });
 
 // Save summary as PDF document.
 await chatCopilot.SaveResponseAsync("message1", "outputPath");
 
 // Save summary with specified format.
 await chatCopilot.SaveResponseAsync("message1", "outputPath", SaveFormat.DocX);
 
 // Save summary as PDF document.
 await chatCopilot.SaveResponseAsync(new List&lt;string&gt;
 {
 "message1",
 "message2"
 }, "outputPath");
 
 // Save summary with specified format.
 await chatCopilot.SaveResponseAsync(new List&lt;string&gt;
 {
 "message1",
 "message2"
 }, "outputPath", SaveFormat.DocX);
 
 // Save the context.
 await chatCopilot.SaveContextAsync("outputPath");
 
 // Delete the context.
 await chatCopilot.DeleteContextAsync();

```csharp
public class OpenAIChatCopilot : IChatCopilot, IAICopilot
```

## Constructors

| Name | Description |
| --- | --- |
| [OpenAIChatCopilot](./openaichatcopilot/#constructor)(*[IOpenAIClient](../../aspose.pdf.ai/iopenaiclient/), IChatCopilotOptions<OpenAIChatCopilotOptions>*) | Initializes a new instance of the [`OpenAIChatCopilot`](../../aspose.pdf.ai/openaichatcopilot/) class with the specified client and options. |

## Properties

| Name | Description |
| --- | --- |
| [HasContext](./hascontext/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| [DeleteContextAsync](./deletecontextasync/)(*Nullable<CancellationToken>*) |  |
| [GetResponseAsync](./getresponseasync/)(*string, Nullable<CancellationToken>*) |  |
| [GetResponseAsync](./getresponseasync/)(*List<string>, Nullable<CancellationToken>*) |  |
| [SaveContextAsync](./savecontextasync/)(*string, Nullable<CancellationToken>*) |  |
| [SaveResponseAsync](./saveresponseasync/)(*string, string, Nullable<CancellationToken>*) |  |
| [SaveResponseAsync](./saveresponseasync/)(*List<string>, string, Nullable<CancellationToken>*) |  |
| [SaveResponseAsync](./saveresponseasync/)(*string, string, SaveFormat, Nullable<CancellationToken>*) |  |
| [SaveResponseAsync](./saveresponseasync/)(*List<string>, string, SaveFormat, Nullable<CancellationToken>*) |  |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

