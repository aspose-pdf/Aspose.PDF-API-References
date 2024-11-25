---
title: Class OpenAIChatCopilot
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAIChatCopilot class. Represents a chat copilot for interacting with documents via AI models. Example usage of creating an OpenAI client configuring options and using the ChatCopilot to interact with user queries and manage conversation context
type: docs
weight: 820
url: /net/aspose.pdf.ai/openaichatcopilot/
---
## OpenAIChatCopilot class

Represents a chat copilot for interacting with documents via AI models. Example usage of creating an OpenAI client, configuring options, and using the ChatCopilot to interact with user queries and manage conversation context.

```csharp
// Create AI client.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// Create copilot options.
var options = OpenAIChatCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...create using delegate.
    .WithModel(OpenAIModels.Gpt35Turbo) // Configure other optional parameters.
    .WithTemperature(0.5)
    .WithTopP(1)
    .WithDocument("DocumentInputPath") // Attach documents using .WithDocument(s) methods allows to add text, pdf and paths to documents.
    .WithContextBackupJsonPath("PathToContextBackup") // Supply context backup to resume the conversation session.
    .WithRestoreContextFromBackup(true); // If set to true, the context 

// Create summary copilot.
var chatCopilot = AICopilotFactory.CreateChatCopilot(openAiClient, options);

// Get response on a user query.
string copilotResponse1 = await chatCopilot.GetResponseAsync("user message");

// Get response on a list of queries.
string copilotResponse2 = await chatCopilot.GetResponseAsync(new List<string>
{
    "message1",
    "message2"
});

// Save summary as PDF document.
await chatCopilot.SaveResponseAsync("message1", "outputPath");

// Save summary with specified format.
await chatCopilot.SaveResponseAsync("message1", "outputPath", SaveFormat.DocX);

// Save summary as PDF document.
await chatCopilot.SaveResponseAsync(new List<string>
{
    "message1",
    "message2"
}, "outputPath");

// Save summary with specified format.
await chatCopilot.SaveResponseAsync(new List<string>
{
    "message1",
    "message2"
}, "outputPath", SaveFormat.DocX);

// Save the context.
await chatCopilot.SaveContextAsync("outputPath");

// Delete the context.
await chatCopilot.DeleteContextAsync();
```

```csharp
public class OpenAIChatCopilot : IChatCopilot
```

## Constructors

| Name | Description |
| --- | --- |
| [OpenAIChatCopilot](openaichatcopilot/)(IOpenAIClient, IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | Initializes a new instance of the `OpenAIChatCopilot` class with the specified client and options. |

## Properties

| Name | Description |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaichatcopilot/hascontext/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/openaichatcopilot/deletecontextasync/)(CancellationToken?) |  |
| [GetResponseAsync](../../aspose.pdf.ai/openaichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) |  |
| [GetResponseAsync](../../aspose.pdf.ai/openaichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) |  |
| [SaveContextAsync](../../aspose.pdf.ai/openaichatcopilot/savecontextasync/)(string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) |  |

### See Also

* interface [IChatCopilot](../ichatcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


