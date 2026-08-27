---
title: "Klass LlamaSummaryCopilot"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.LlamaSummaryCopilot-klass. Tillhandahåller funktionalitet för att hämta dokumentsammanfattningar med AI-modeller. Exempel på användning av att skapa en Llama-klient, konfigurera alternativ och använda sammanfattnings‑copiloten. Obs! Denna copilot använder completions‑API så den totala mängden text som kan skickas är begränsad av modellens kontextfönster."
type: docs
weight: 790
url: /sv/net/aspose.pdf.ai/llamasummarycopilot/
---
## LlamaSummaryCopilot class

Tillhandahåller funktionalitet för att hämta dokumentsammanfattningar med AI-modeller. Exempel på användning av att skapa en Llama-klient, konfigurera alternativ och använda sammanfattnings‑copiloten. Obs: Denna copilot använder completions‑API, så den totala mängden text som kan skickas är begränsad av modellens kontextfönster.

```csharp
// Skapa AI‑klient.
var llamaClient = LlamaClient
   .CreateWithApiKey(ApiKey) // Create Llama client with the API key.
   .Build();

// Skapa copilot‑alternativ.
var options = LlamaSummaryCopilotOptions
   .Create() // Create options like this, or...
   //.Create(options => { options.Model = LlamaModels.Llama13BChat; }) // ...skapa med delegat.
   .WithTemperature(0.5) // Configure other optional parameters.
   .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
   .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// Skapa sammanfattnings‑copilot.
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(llamaClient, options);

// Hämta sammanfattningstext.
string summaryText = await summaryCopilot.GetSummaryAsync();

// Hämta sammanfattningsdokument.
Document summaryDocument = await summaryCopilot.GetSummaryDocumentAsync();

// Hämta sammanfattningsdokument med sidinformation.
Document summaryDocumentWithPageInfo = await summaryCopilot.GetSummaryDocumentAsync(new PageInfo());

// Spara sammanfattning som PDF‑dokument.
await summaryCopilot.SaveSummaryAsync("outputPath");

// Spara sammanfattning med angivet format.
await summaryCopilot.SaveSummaryAsync("outputPath", SaveFormat.DocX);
```

```csharp
public class LlamaSummaryCopilot : ISummaryCopilot
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [LlamaSummaryCopilot](llamasummarycopilot/)(ILlamaClient, ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | Initierar en ny instans av `LlamaSummaryCopilot`-klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/llamasummarycopilot/hascontext/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### Se även

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


