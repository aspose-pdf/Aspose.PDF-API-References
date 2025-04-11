---
title: Class OpenAIChatCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.OpenAIChatCopilotOptions. Rappresenta le opzioni per configurare l'OpenAICopilot
type: docs
weight: 830
url: /it/net/aspose.pdf.ai/openaichatcopilotoptions/
---
## Classe OpenAIChatCopilotOptions

Rappresenta le opzioni per configurare l'OpenAICopilot.

```csharp
public class OpenAIChatCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IChatCopilotOptions<OpenAIChatCopilotOptions>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/assistantname/) { get; set; } | Ottiene o imposta il nome dell'assistente. |
| [ContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/contextbackupjsonpath/) { get; set; } | Ottiene o imposta il percorso del file per il backup del contesto JSON. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Ottiene o imposta la collezione di documenti da elaborare. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Ottiene o imposta il numero massimo di token di completamento che possono essere utilizzati durante l'esecuzione. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Ottiene o imposta il numero massimo di token di prompt che possono essere utilizzati durante l'esecuzione. |
| virtual [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Ottiene o imposta il modello da utilizzare per l'assistente. |
| [RestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/restorecontextfrombackup/) { get; set; } | Ottiene o imposta un valore che indica se ripristinare il contesto dal backup. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Ottiene o imposta il percorso del file per il file di testo contenente le istruzioni di sistema dell'assistente. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Ottiene o imposta la temperatura di campionamento da utilizzare per il modello. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Ottiene o imposta il valore top-p per il campionamento del nucleo. |
| [TruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/truncationstrategy/) { get; set; } | Ottiene o imposta la strategia di troncamento per il thread. |
| [VectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/vectorstoreexpiredays/) { get; set; } | Ottiene o imposta il numero di giorni prima che il negozio di vettori scada. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create)() | Crea una nuova istanza di `OpenAIChatCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create_1)(Action&lt;OpenAIChatCopilotOptions&gt;) | Crea un'istanza di `OpenAIChatCopilotOptions` e la configura utilizzando il delegato fornito. |
| [GetOptions](../../aspose.pdf.ai/openaichatcopilotoptions/getoptions/)() | Ottiene le attuali `OpenAIChatCopilotOptions`. |
| [WithAssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/withassistantname/)(string) | Imposta il nome dell'assistente per le opzioni del chat copilot. |
| [WithContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/withcontextbackupjsonpath/)(string) | Imposta il percorso del file per il backup del contesto JSON nelle opzioni del chat copilot. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument)(PdfDocument) | Aggiunge un documento PDF alla collezione di documenti per le opzioni del chat copilot. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_2)(string) | Aggiunge un percorso di documento alla collezione di documenti per le opzioni del chat copilot. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_1)(TextDocument) | Aggiunge un documento di testo alla collezione di documenti per le opzioni del chat copilot. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Imposta la collezione di documenti per le opzioni del chat copilot. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Aggiunge più documenti PDF alla collezione di documenti per le opzioni del chat copilot. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Aggiunge più percorsi di documenti alla collezione di documenti per le opzioni del chat copilot. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Aggiunge più documenti di testo alla collezione di documenti per le opzioni del chat copilot. |
| [WithInstructions](../../aspose.pdf.ai/openaichatcopilotoptions/withinstructions/)(string) | Imposta le istruzioni per le opzioni del chat copilot. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxcompletiontokens/)(int?) | Imposta i token di completamento massimi per le opzioni del chat copilot. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxprompttokens/)(int?) | Imposta i token di prompt massimi per le opzioni del chat copilot. |
| [WithModel](../../aspose.pdf.ai/openaichatcopilotoptions/withmodel/)(string) | Imposta il modello per le opzioni del chat copilot. |
| [WithRestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/withrestorecontextfrombackup/)(bool) | Imposta se ripristinare il contesto dal backup nelle opzioni del chat copilot. |
| [WithTemperature](../../aspose.pdf.ai/openaichatcopilotoptions/withtemperature/)(double?) | Imposta la temperatura per le opzioni del chat copilot. |
| [WithTopP](../../aspose.pdf.ai/openaichatcopilotoptions/withtopp/)(double?) | Imposta il valore top P per le opzioni del chat copilot. |
| [WithTruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/withtruncationstrategy/)(TruncationStrategy) | Imposta la strategia di troncamento per le opzioni del chat copilot. |
| [WithVectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/withvectorstoreexpiredays/)(int) | Imposta il numero di giorni per la scadenza del negozio di vettori nelle opzioni del chat copilot. |

### Vedi anche

* classe [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interfaccia [IChatCopilotOptions&lt;TOptions&gt;](../ichatcopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)