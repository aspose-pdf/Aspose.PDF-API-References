---
title: "Classe OpenAISummaryCopilot"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.AI.OpenAISummaryCopilot. Fornisce funzionalità per ottenere riepiloghi dei documenti usando modelli AI. Esempio di utilizzo per creare un client OpenAI configurando le opzioni e usando il summary copilot."
type: docs
weight: 1000
url: /it/net/aspose.pdf.ai/openaisummarycopilot/
---
## OpenAISummaryCopilot class

Fornisce funzionalità per ottenere riepiloghi dei documenti usando modelli AI. Esempio di utilizzo per creare un client OpenAI, configurare le opzioni e utilizzare il copilot di riepilogo.

```csharp
// Crea client AI.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .Build();

// Crea opzioni per il copilot.
var options = OpenAISummaryCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...crea usando il delegato.
    .WithTemperature(0.5) // Configure other optional parameters.
    .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
    .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// Crea copilot di riepilogo.
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(openAiClient, options);

// Ottieni testo del riepilogo.
string summaryText = await summaryCopilot.GetSummaryAsync();

// Ottieni documento di riepilogo.
Document summaryDocument = await summaryCopilot.GetSummaryDocumentAsync();

// Ottieni documento di riepilogo con informazioni sulla pagina.
Document summaryDocumentWithPageInfo = await summaryCopilot.GetSummaryDocumentAsync(new PageInfo());

// Salva il riepilogo come documento PDF.
await summaryCopilot.SaveSummaryAsync("outputPath");

// Salva il riepilogo con il formato specificato.
await summaryCopilot.SaveSummaryAsync("outputPath", SaveFormat.DocX);
```

```csharp
public class OpenAISummaryCopilot : ISummaryCopilot
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [OpenAISummaryCopilot](openaisummarycopilot/)(IOpenAIClient, ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Inizializza una nuova istanza della classe `OpenAISummaryCopilot`. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaisummarycopilot/hascontext/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### Vedi anche

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


