---
title: Class OpenAISummaryCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.OpenAISummaryCopilotOptions. Rappresenta le opzioni per configurare l'OpenAICopilot
type: docs
weight: 930
url: /it/net/aspose.pdf.ai/openaisummarycopilotoptions/
---
## Classe OpenAISummaryCopilotOptions

Rappresenta le opzioni per configurare l'OpenAICopilot.

```csharp
public class OpenAISummaryCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    ISummaryCopilotOptions<OpenAISummaryCopilotOptions>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/assistantname/) { get; set; } | Ottiene o imposta il nome dell'assistente. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Ottiene o imposta la collezione di documenti da elaborare. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Ottiene o imposta il numero massimo di token di completamento che possono essere utilizzati durante l'esecuzione. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Ottiene o imposta il numero massimo di token di prompt che possono essere utilizzati durante l'esecuzione. |
| virtual [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Ottiene o imposta il modello da utilizzare per l'assistente. |
| [SummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/summaryprompt/) { get; set; } | Ottiene o imposta il prompt per istruire il modello a fornire un riepilogo del documento. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Ottiene o imposta il percorso del file per il file di testo contenente le istruzioni di sistema dell'assistente. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Ottiene o imposta la temperatura di campionamento da utilizzare per il modello. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Ottiene o imposta il valore top-p per il campionamento del nucleo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create)() | Crea una nuova istanza di `OpenAISummaryCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create_1)(Action&lt;OpenAISummaryCopilotOptions&gt;) | Crea un'istanza di `OpenAISummaryCopilotOptions` e la configura utilizzando il delegato fornito. |
| [GetOptions](../../aspose.pdf.ai/openaisummarycopilotoptions/getoptions/)() | Ottiene le attuali `OpenAISummaryCopilotOptions`. |
| [WithAssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/withassistantname/)(string) | Imposta il nome dell'assistente per le opzioni del copilot di riepilogo. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | Aggiunge un documento PDF alla collezione di documenti per le opzioni del copilot di riepilogo. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_2)(string) | Aggiunge un percorso di documento alla collezione di documenti per le opzioni del copilot di riepilogo. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | Aggiunge un documento di testo alla collezione di documenti per le opzioni del copilot di riepilogo. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Imposta la collezione di documenti per le opzioni del copilot di riepilogo. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Aggiunge più documenti PDF alla collezione di documenti per le opzioni del copilot di riepilogo. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Aggiunge più percorsi di documenti alla collezione di documenti per le opzioni del copilot di riepilogo. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Aggiunge più documenti di testo alla collezione di documenti per le opzioni del copilot di riepilogo. |
| [WithInstructions](../../aspose.pdf.ai/openaisummarycopilotoptions/withinstructions/)(string) | Imposta le istruzioni per le opzioni del copilot di riepilogo. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxcompletiontokens/)(int?) | Imposta i token di completamento massimi per le opzioni del copilot di riepilogo. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxprompttokens/)(int?) | Imposta i token di prompt massimi per le opzioni del copilot di riepilogo. |
| [WithModel](../../aspose.pdf.ai/openaisummarycopilotoptions/withmodel/)(string) | Imposta il modello per le opzioni del copilot di riepilogo. |
| [WithSummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/withsummaryprompt/)(string) | Imposta il prompt di riepilogo per le opzioni del copilot di riepilogo. |
| [WithTemperature](../../aspose.pdf.ai/openaisummarycopilotoptions/withtemperature/)(double?) | Imposta la temperatura per le opzioni del copilot di riepilogo. |
| [WithTopP](../../aspose.pdf.ai/openaisummarycopilotoptions/withtopp/)(double?) | Imposta il valore top P per le opzioni del copilot di riepilogo. |

### Vedi anche

* classe [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interfaccia [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)