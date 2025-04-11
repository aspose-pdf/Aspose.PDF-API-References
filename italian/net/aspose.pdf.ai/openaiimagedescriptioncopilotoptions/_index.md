---
title: Class OpenAIImageDescriptionCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.OpenAIImageDescriptionCopilotOptions. Rappresenta le opzioni per configurare l'OpenAICopilot
type: docs
weight: 900
url: /it/net/aspose.pdf.ai/openaiimagedescriptioncopilotoptions/
---
## OpenAIImageDescriptionCopilotOptions class

Rappresenta le opzioni per configurare l'OpenAICopilot.

```csharp
public class OpenAIImageDescriptionCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IImageDescriptionCopilotOptions<OpenAIImageDescriptionCopilotOptions>
```

## Properties

| Name | Description |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/assistantname/) { get; set; } | Ottiene o imposta il nome dell'assistente. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Ottiene o imposta la collezione di documenti da elaborare. |
| [ImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedescriptionprompt/) { get; set; } | Ottiene o imposta il prompt per istruire il modello a fornire una descrizione dell'immagine. |
| [ImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedetail/) { get; set; } | Ottiene o imposta il livello di dettaglio dell'immagine se specificato dall'utente. "low" utilizza meno token, puoi optare per un'alta risoluzione usando "high". Se non impostato, predefinito su "auto". |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Ottiene o imposta il numero massimo di token di completamento che possono essere utilizzati durante l'esecuzione. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Ottiene o imposta il numero massimo di token di prompt che possono essere utilizzati durante l'esecuzione. |
| override [Model](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/model/) { get; set; } | Ottiene o imposta il modello di visione da utilizzare per l'assistente. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Ottiene o imposta il percorso del file per il file di testo contenente le istruzioni di sistema dell'assistente. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Ottiene o imposta la temperatura di campionamento da utilizzare per il modello. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Ottiene o imposta il valore top-p per il campionamento del nucleo. |

## Methods

| Name | Description |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create)() | Crea una nuova istanza di `OpenAIImageDescriptionCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create_1)(Action&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Crea un'istanza di `OpenAIImageDescriptionCopilotOptions` e la configura utilizzando il delegato fornito. |
| [GetOptions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/getoptions/)() | Ottiene le attuali `OpenAIImageDescriptionCopilotOptions`. |
| [WithAssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withassistantname/)(string) | Imposta il nome dell'assistente per le opzioni del copilot di descrizione dell'immagine. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument)(PdfDocument) | Aggiunge un documento PDF alla collezione di documenti per le opzioni del copilot di descrizione dell'immagine. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument_1)(string) | Aggiunge un percorso di documento alla collezione di documenti per le opzioni del copilot di descrizione dell'immagine. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Imposta la collezione di documenti per le opzioni del copilot di descrizione dell'immagine. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Aggiunge più documenti PDF alla collezione di documenti per le opzioni del copilot di descrizione dell'immagine. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | Aggiunge più percorsi di documenti alla collezione di documenti per le opzioni del copilot di descrizione dell'immagine. |
| [WithImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedescriptionprompt/)(string) | Imposta il prompt per le opzioni del copilot di descrizione dell'immagine. |
| [WithImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedetail/)(string) | Imposta il livello di dettaglio dell'immagine. |
| [WithInstructions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withinstructions/)(string) | Imposta le istruzioni per le opzioni del copilot di descrizione dell'immagine. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxcompletiontokens/)(int?) | Imposta i token di completamento massimi per le opzioni del copilot di descrizione dell'immagine. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxprompttokens/)(int?) | Imposta i token di prompt massimi per le opzioni del copilot di descrizione dell'immagine. |
| [WithModel](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmodel/)(string) | Imposta il modello per le opzioni del copilot di descrizione dell'immagine. |
| [WithTemperature](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtemperature/)(double?) | Imposta la temperatura per le opzioni del copilot di descrizione dell'immagine. |
| [WithTopP](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtopp/)(double?) | Imposta il valore top P per le opzioni del copilot di descrizione dell'immagine. |

### See Also

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IImageDescriptionCopilotOptions&lt;TOptions&gt;](../iimagedescriptioncopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)