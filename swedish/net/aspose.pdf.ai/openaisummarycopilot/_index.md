---
title: "Klass OpenAISummaryCopilot"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.OpenAISummaryCopilot-klass. Tillhandahåller funktionalitet för att hämta dokumentsammanfattningar med AI‑modeller. Exempel på hur man skapar en OpenAI‑klient, konfigurerar alternativ och använder sammanfattnings‑copiloten."
type: docs
weight: 1000
url: /sv/net/aspose.pdf.ai/openaisummarycopilot/
---
## OpenAISummaryCopilot class

Tillhandahåller funktionalitet för att hämta dokumentsammanfattningar med AI‑modeller. Exempel på användning av att skapa en OpenAI‑klient, konfigurera alternativ och använda sammanfattnings‑copilot.

```csharp
// Skapa AI‑klient.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .Build();

// Skapa copilot‑alternativ.
var options = OpenAISummaryCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...create using delegate.
    .WithTemperature(0.5) // Configure other optional parameters.
    .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
    .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// Skapa sammanfattnings‑copilot.
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(openAiClient, options);

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
public class OpenAISummaryCopilot : ISummaryCopilot
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [OpenAISummaryCopilot](openaisummarycopilot/)(IOpenAIClient, ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Initierar en ny instans av klassen `OpenAISummaryCopilot`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaisummarycopilot/hascontext/) { get; } |  |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### Se även

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


