---
title: Class LlamaSummaryCopilot
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.LlamaSummaryCopilot. Fornisce funzionalità per ottenere riassunti di documenti utilizzando modelli AI. Esempio di utilizzo per creare un client Llama, configurare opzioni e utilizzare il copilot di riassunto. Nota Questo copilot utilizza l'API di completamento, quindi la quantità totale di testo che può essere inviata è limitata dalla finestra di contesto del modello.
type: docs
weight: 740
url: /it/net/aspose.pdf.ai/llamasummarycopilot/
---
## Classe LlamaSummaryCopilot

Fornisce funzionalità per ottenere riassunti di documenti utilizzando modelli AI. Esempio di utilizzo per creare un client Llama, configurare opzioni e utilizzare il copilot di riassunto. Nota: Questo copilot utilizza l'API di completamento, quindi la quantità totale di testo che può essere inviata è limitata dalla finestra di contesto del modello.

```csharp
// Create AI client.
var llamaClient = LlamaClient
   .CreateWithApiKey(ApiKey) // Create Llama client with the API key.
   .Build();

// Create copilot options.
var options = LlamaSummaryCopilotOptions
   .Create() // Create options like this, or...
   //.Create(options => { options.Model = LlamaModels.Llama13BChat; }) // ...create using delegate.
   .WithTemperature(0.5) // Configure other optional parameters.
   .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
   .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// Create summary copilot.
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(llamaClient, options);

// Get summary text.
string summaryText = await summaryCopilot.GetSummaryAsync();

// Get summary document.
Document summaryDocument = await summaryCopilot.GetSummaryDocumentAsync();

// Get summary document with page info.
Document summaryDocumentWithPageInfo = await summaryCopilot.GetSummaryDocumentAsync(new PageInfo());

// Save summary as PDF document.
await summaryCopilot.SaveSummaryAsync("outputPath");

// Save summary with specified format.
await summaryCopilot.SaveSummaryAsync("outputPath", SaveFormat.DocX);
```

```csharp
public class LlamaSummaryCopilot : ISummaryCopilot
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [LlamaSummaryCopilot](llamasummarycopilot/)(ILlamaClient, ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | Inizializza una nuova istanza della classe `LlamaSummaryCopilot`. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/llamasummarycopilot/hascontext/) { get; } |  |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### Vedi Anche

* interfaccia [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)