---
title: "Klass OpenAIChatCopilot"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.OpenAIChatCopilot-klass. Representerar en chatt‑copilot för att interagera med dokument via AI‑modeller. Exempel på användning av att skapa en OpenAI‑klient, konfigurera alternativ och använda ChatCopilot för att interagera med användarfrågor och hantera konversationskontext."
type: docs
weight: 880
url: /sv/net/aspose.pdf.ai/openaichatcopilot/
---
## OpenAIChatCopilot class

Representerar en chatt‑copilot för att interagera med dokument via AI‑modeller. Exempel på användning av att skapa en OpenAI‑klient, konfigurera alternativ och använda ChatCopilot för att interagera med användarfrågor och hantera samtalskontext.

```csharp
// Skapa AI‑klient.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// Skapa copilot‑alternativ.
var options = OpenAIChatCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...create using delegate.
    .WithModel(OpenAIModels.Gpt35Turbo) // Configure other optional parameters.
    .WithTemperature(0.5)
    .WithTopP(1)
    .WithDocument("DocumentInputPath") // Attach documents using .WithDocument(s) methods allows to add text, pdf and paths to documents.
    .WithContextBackupJsonPath("PathToContextBackup") // Supply context backup to resume the conversation session.
    .WithRestoreContextFromBackup(true); // If set to true, the context 

// Skapa sammanfattnings‑copilot.
var chatCopilot = AICopilotFactory.CreateChatCopilot(openAiClient, options);

// Hämta svar på en användarfråga.
string copilotResponse1 = await chatCopilot.GetResponseAsync("user message");

// Hämta svar på en lista med frågor.
string copilotResponse2 = await chatCopilot.GetResponseAsync(new List<string>
{
    "message1",
    "message2"
});

// Spara sammanfattning som PDF‑dokument.
await chatCopilot.SaveResponseAsync("message1", "outputPath");

// Spara sammanfattning med angivet format.
await chatCopilot.SaveResponseAsync("message1", "outputPath", SaveFormat.DocX);

// Spara sammanfattning som PDF‑dokument.
await chatCopilot.SaveResponseAsync(new List<string>
{
    "message1",
    "message2"
}, "outputPath");

// Spara sammanfattning med angivet format.
await chatCopilot.SaveResponseAsync(new List<string>
{
    "message1",
    "message2"
}, "outputPath", SaveFormat.DocX);

// Spara kontexten.
await chatCopilot.SaveContextAsync("outputPath");

// Ta bort kontexten.
await chatCopilot.DeleteContextAsync();
```

```csharp
public class OpenAIChatCopilot : IChatCopilot
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [OpenAIChatCopilot](openaichatcopilot/)(IOpenAIClient, IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | Initierar en ny instans av `OpenAIChatCopilot`-klassen med den angivna klienten och alternativen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaichatcopilot/hascontext/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/openaichatcopilot/deletecontextasync/)(CancellationToken?) |  |
| [GetResponseAsync](../../aspose.pdf.ai/openaichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) |  |
| [GetResponseAsync](../../aspose.pdf.ai/openaichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) |  |
| [SaveContextAsync](../../aspose.pdf.ai/openaichatcopilot/savecontextasync/)(string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) |  |

### Se även

* interface [IChatCopilot](../ichatcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


