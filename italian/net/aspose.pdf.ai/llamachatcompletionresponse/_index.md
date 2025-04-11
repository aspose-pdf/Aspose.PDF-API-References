---
title: Class LlamaChatCompletionResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.LlamaChatCompletionResponse. Rappresenta una risposta di completamento della chat restituita dal modello basata sull'input fornito
type: docs
weight: 690
url: /it/net/aspose.pdf.ai/llamachatcompletionresponse/
---
## Classe LlamaChatCompletionResponse

Rappresenta una risposta di completamento della chat restituita dal modello, basata sull'input fornito.

```csharp
public class LlamaChatCompletionResponse : BaseResponse
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [LlamaChatCompletionResponse](llamachatcompletionresponse/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Choices](../../aspose.pdf.ai/llamachatcompletionresponse/choices/) { get; set; } | Ottiene o imposta un elenco di scelte di completamento della chat. Può essere più di uno se n è maggiore di 1. |
| [Created](../../aspose.pdf.ai/llamachatcompletionresponse/created/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) di quando è stato creato il completamento della chat. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ottiene o imposta il dettaglio della risposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ottiene o imposta l'errore della risposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ottiene o imposta le informazioni sull'errore. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ottiene o imposta le intestazioni della risposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ottiene o imposta il codice di stato HTTP. |
| [Id](../../aspose.pdf.ai/llamachatcompletionresponse/id/) { get; set; } | Ottiene o imposta un identificatore univoco per il completamento della chat. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se la risposta è stata positiva. |
| [Model](../../aspose.pdf.ai/llamachatcompletionresponse/model/) { get; set; } | Ottiene o imposta il modello utilizzato per il completamento della chat. |
| [Object](../../aspose.pdf.ai/llamachatcompletionresponse/object/) { get; set; } | Ottiene o imposta il tipo di oggetto, che è sempre chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ottiene la frase di ragione dell'errore. |
| [SystemFingerprint](../../aspose.pdf.ai/llamachatcompletionresponse/systemfingerprint/) { get; set; } | Ottiene o imposta l'impronta digitale che rappresenta la configurazione del backend con cui il modello viene eseguito. |
| [Usage](../../aspose.pdf.ai/llamachatcompletionresponse/usage/) { get; set; } | Ottiene o imposta le statistiche di utilizzo per la richiesta di completamento. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/llamachatcompletionresponse/tostring/)() | Restituisce una rappresentazione stringa della prima scelta. |

### Vedi Anche

* classe [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)