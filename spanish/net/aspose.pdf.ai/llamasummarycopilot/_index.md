---
title: Class LlamaSummaryCopilot
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.LlamaSummaryCopilot. Proporciona funcionalidad para obtener resúmenes de documentos utilizando modelos de IA. Ejemplo de uso de la creación de un cliente Llama, configurando opciones y utilizando el copiloto de resumen. Nota Este copiloto utiliza la API de finalización, por lo que la cantidad total de texto que se puede enviar está limitada por la ventana de contexto del modelo.
type: docs
weight: 740
url: /es/net/aspose.pdf.ai/llamasummarycopilot/
---
## Clase LlamaSummaryCopilot

Proporciona funcionalidad para obtener resúmenes de documentos utilizando modelos de IA. Ejemplo de uso de la creación de un cliente Llama, configurando opciones y utilizando el copiloto de resumen. Nota: Este copiloto utiliza la API de finalización, por lo que la cantidad total de texto que se puede enviar está limitada por la ventana de contexto del modelo.

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

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LlamaSummaryCopilot](llamasummarycopilot/)(ILlamaClient, ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | Inicializa una nueva instancia de la clase `LlamaSummaryCopilot`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/llamasummarycopilot/hascontext/) { get; } |  |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### Véase También

* interfaz [ISummaryCopilot](../isummarycopilot/)
* espacio de nombres [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* ensamblado [Aspose.PDF](../../)