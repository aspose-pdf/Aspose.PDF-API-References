---
title: Class LlamaSummaryCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.LlamaSummaryCopilotOptions classe. Rappresenta le opzioni per configurare l'OpenAICopilot.
type: docs
weight: 750
url: /it/net/aspose.pdf.ai/llamasummarycopilotoptions/
---
## Classe LlamaSummaryCopilotOptions

Rappresenta le opzioni per configurare l'OpenAICopilot.

```csharp
public class LlamaSummaryCopilotOptions : LlamaCopilotOptionsBase, 
    ISummaryCopilotOptions<LlamaSummaryCopilotOptions>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DocumentCollection](../../aspose.pdf.ai/llamacopilotoptionsbase/documentcollection/) { get; set; } | Ottiene o imposta la collezione di documenti da elaborare. |
| [MaxCompletionTokens](../../aspose.pdf.ai/llamacopilotoptionsbase/maxcompletiontokens/) { get; set; } | Ottiene o imposta il numero massimo di token di completamento che possono essere utilizzati durante l'esecuzione. |
| virtual [Model](../../aspose.pdf.ai/llamacopilotoptionsbase/model/) { get; set; } | Ottiene o imposta il modello da utilizzare per l'assistente. |
| [SummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/summaryprompt/) { get; set; } | Ottiene o imposta il prompt per istruire il modello a fornire un riepilogo del documento. |
| [SystemInstructions](../../aspose.pdf.ai/llamacopilotoptionsbase/systeminstructions/) { get; set; } | Ottiene o imposta il percorso del file per il file di testo contenente le istruzioni di sistema dell'assistente. |
| [Temperature](../../aspose.pdf.ai/llamacopilotoptionsbase/temperature/) { get; set; } | Ottiene o imposta la temperatura di campionamento da utilizzare per il modello. |
| [TopP](../../aspose.pdf.ai/llamacopilotoptionsbase/topp/) { get; set; } | Ottiene o imposta il valore top-p per il campionamento del nucleo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create)() | Crea una nuova istanza di `LlamaSummaryCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create_1)(Action&lt;LlamaSummaryCopilotOptions&gt;) | Crea un'istanza di `LlamaSummaryCopilotOptions` e la configura utilizzando il delegato fornito. |
| [GetOptions](../../aspose.pdf.ai/llamasummarycopilotoptions/getoptions/)() | Ottiene le attuali `LlamaSummaryCopilotOptions`. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | Aggiunge un documento PDF alla collezione di documenti per le opzioni del copilot di riepilogo. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_2)(string) | Aggiunge un percorso di documento alla collezione di documenti per le opzioni del copilot di riepilogo. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | Aggiunge un documento di testo alla collezione di documenti per le opzioni del copilot di riepilogo. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Imposta la collezione di documenti per le opzioni del copilot di riepilogo. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Aggiunge più documenti PDF alla collezione di documenti per le opzioni del copilot di riepilogo. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Aggiunge più percorsi di documenti alla collezione di documenti per le opzioni del copilot di riepilogo. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Aggiunge più documenti di testo alla collezione di documenti per le opzioni del copilot di riepilogo. |
| [WithInstructions](../../aspose.pdf.ai/llamasummarycopilotoptions/withinstructions/)(string) | Imposta le istruzioni per le opzioni del copilot di riepilogo. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/llamasummarycopilotoptions/withmaxcompletiontokens/)(int?) | Imposta i token di completamento massimi per le opzioni del copilot di riepilogo. |
| [WithModel](../../aspose.pdf.ai/llamasummarycopilotoptions/withmodel/)(string) | Imposta il modello per le opzioni del copilot di riepilogo. |
| [WithSummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/withsummaryprompt/)(string) | Imposta il prompt di riepilogo per le opzioni del copilot di riepilogo. |
| [WithTemperature](../../aspose.pdf.ai/llamasummarycopilotoptions/withtemperature/)(double?) | Imposta la temperatura per le opzioni del copilot di riepilogo. |
| [WithTopP](../../aspose.pdf.ai/llamasummarycopilotoptions/withtopp/)(double?) | Imposta il valore top P per le opzioni del copilot di riepilogo. |

### Vedi Anche

* classe [LlamaCopilotOptionsBase](../llamacopilotoptionsbase/)
* interfaccia [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)