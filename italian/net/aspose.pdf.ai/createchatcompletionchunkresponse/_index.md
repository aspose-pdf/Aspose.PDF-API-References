---
title: Class CreateChatCompletionChunkResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.CreateChatCompletionChunkResponse. Rappresenta un chunk in streaming di una risposta di completamento chat restituita dal modello basato sull'input fornito
type: docs
weight: 250
url: /it/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## Classe CreateChatCompletionChunkResponse

Rappresenta un chunk in streaming di una risposta di completamento chat restituita dal modello, basata sull'input fornito.

```csharp
public class CreateChatCompletionChunkResponse
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [CreateChatCompletionChunkResponse](createchatcompletionchunkresponse/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | Ottiene o imposta un elenco di scelte di completamento chat. Può contenere più di un elemento se n è maggiore di 1. Può anche essere vuoto per l'ultimo chunk se imposti stream_options: {"include_usage": true}. |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) di quando è stato creato il completamento chat. Ogni chunk ha lo stesso timestamp. |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | Ottiene o imposta un identificatore univoco per il completamento chat. Ogni chunk ha lo stesso ID. |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | Ottiene o imposta il modello per generare il completamento. |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | Ottiene o imposta il tipo di oggetto, che è sempre chat.completion.chunk. |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | Ottiene o imposta l'impronta digitale che rappresenta la configurazione del backend con cui il modello viene eseguito. Può essere utilizzata insieme al parametro di richiesta seed per comprendere quando sono state apportate modifiche al backend che potrebbero influenzare il determinismo. |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | Ottiene o imposta un campo facoltativo che sarà presente solo quando imposti stream_options: {"include_usage": true} nella tua richiesta. Quando presente, contiene un valore nullo tranne per l'ultimo chunk che contiene le statistiche di utilizzo dei token per l'intera richiesta. |

### Vedi Anche

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)