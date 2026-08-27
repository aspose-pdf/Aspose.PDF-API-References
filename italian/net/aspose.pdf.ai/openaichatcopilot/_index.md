---
title: "Classe OpenAIChatCopilot"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.AI.OpenAIChatCopilot. Rappresenta un copilot di chat per interagire con i documenti tramite modelli AI. Esempio di utilizzo per creare un client OpenAI, configurare le opzioni e usare il ChatCopilot per interagire con le richieste degli utenti e gestire il contesto della conversazione"
type: docs
weight: 880
url: /it/net/aspose.pdf.ai/openaichatcopilot/
---
## OpenAIChatCopilot class

Rappresenta un copilot di chat per interagire con i documenti tramite modelli AI. Esempio di utilizzo per creare un client OpenAI, configurare le opzioni e utilizzare il ChatCopilot per interagire con le richieste degli utenti e gestire il contesto della conversazione.

```csharp
// Crea client AI.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .WithOrganization("org_123")
    .Build(); // Build.

// Crea opzioni per il copilot.
var options = OpenAIChatCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...crea usando il delegato.
    .WithModel(OpenAIModels.Gpt35Turbo) // Configure other optional parameters.
    .WithTemperature(0.5)
    .WithTopP(1)
    .WithDocument("DocumentInputPath") // Attach documents using .WithDocument(s) methods allows to add text, pdf and paths to documents.
    .WithContextBackupJsonPath("PathToContextBackup") // Supply context backup to resume the conversation session.
    .WithRestoreContextFromBackup(true); // If set to true, the context 

// Crea copilot di riepilogo.
var chatCopilot = AICopilotFactory.CreateChatCopilot(openAiClient, options);

// Ottieni risposta a una query dell'utente.
string copilotResponse1 = await chatCopilot.GetResponseAsync("user message");

// Ottieni risposta a un elenco di query.
string copilotResponse2 = await chatCopilot.GetResponseAsync(new List<string>
{
    "message1",
    "message2"
});

// Salva il riepilogo come documento PDF.
await chatCopilot.SaveResponseAsync("message1", "outputPath");

// Salva il riepilogo con il formato specificato.
await chatCopilot.SaveResponseAsync("message1", "outputPath", SaveFormat.DocX);

// Salva il riepilogo come documento PDF.
await chatCopilot.SaveResponseAsync(new List<string>
{
    "message1",
    "message2"
}, "outputPath");

// Salva il riepilogo con il formato specificato.
await chatCopilot.SaveResponseAsync(new List<string>
{
    "message1",
    "message2"
}, "outputPath", SaveFormat.DocX);

// Salva il contesto.
await chatCopilot.SaveContextAsync("outputPath");

// Elimina il contesto.
await chatCopilot.DeleteContextAsync();
```

```csharp
public class OpenAIChatCopilot : IChatCopilot
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [OpenAIChatCopilot](openaichatcopilot/)(IOpenAIClient, IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | Inizializza una nuova istanza della classe `OpenAIChatCopilot` con il client e le opzioni specificati. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaichatcopilot/hascontext/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [DeleteContextAsync](../../aspose.pdf.ai/openaichatcopilot/deletecontextasync/)(CancellationToken?) |  |
| [GetResponseAsync](../../aspose.pdf.ai/openaichatcopilot/getresponseasync/#getresponseasync)(List&lt;string&gt;, CancellationToken?) |  |
| [GetResponseAsync](../../aspose.pdf.ai/openaichatcopilot/getresponseasync/#getresponseasync_1)(string, CancellationToken?) |  |
| [SaveContextAsync](../../aspose.pdf.ai/openaichatcopilot/savecontextasync/)(string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_1)(List&lt;string&gt;, string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_3)(string, string, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync)(List&lt;string&gt;, string, SaveFormat, CancellationToken?) |  |
| [SaveResponseAsync](../../aspose.pdf.ai/openaichatcopilot/saveresponseasync/#saveresponseasync_2)(string, string, SaveFormat, CancellationToken?) |  |

### Vedi anche

* interface [IChatCopilot](../ichatcopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


