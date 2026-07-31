---
title: "Classe LlamaSummaryCopilot"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.AI.LlamaSummaryCopilot. Fornisce funzionalità per ottenere riepiloghi di documenti utilizzando modelli AI. Esempio di utilizzo per creare un client Llama configurando le opzioni e usando il copilot di riepilogo. Nota: questo copilot utilizza l'API di completamento, quindi la quantità totale di testo che può essere inviata è limitata dalla finestra di contesto del modello."
type: docs
weight: 790
url: /it/net/aspose.pdf.ai/llamasummarycopilot/
---
## LlamaSummaryCopilot class

Fornisce funzionalità per ottenere riepiloghi di documenti utilizzando modelli AI. Esempio di utilizzo per creare un client Llama, configurare le opzioni e utilizzare il copilot di riepilogo. Nota: questo copilot utilizza l'API di completamento, quindi la quantità totale di testo che può essere inviata è limitata dalla finestra di contesto del modello.

```csharp
// Crea client AI.
var llamaClient = LlamaClient
   .CreateWithApiKey(ApiKey) // Create Llama client with the API key.
   .Build();

// Crea opzioni per il copilot.
var options = LlamaSummaryCopilotOptions
   .Create() // Create options like this, or...
   //.Create(options => { options.Model = LlamaModels.Llama13BChat; }) // ...create using delegate.
   .WithTemperature(0.5) // Configure other optional parameters.
   .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
   .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// Crea copilot di riepilogo.
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(llamaClient, options);

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

### Vedi anche

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


