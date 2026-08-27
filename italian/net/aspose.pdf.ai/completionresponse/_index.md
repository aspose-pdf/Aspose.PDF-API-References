---
title: "Classe CompletionResponse"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.AI.CompletionResponse. Rappresenta una risposta di completamento della chat restituita dal modello in base all'input fornito"
type: docs
weight: 250
url: /it/net/aspose.pdf.ai/completionresponse/
---
## CompletionResponse class

Rappresenta una risposta di completamento della chat restituita dal modello, basata sull'input fornito.

```csharp
public class CompletionResponse : BaseResponse
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [CompletionResponse](completionresponse/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Choices](../../aspose.pdf.ai/completionresponse/choices/) { get; set; } | Ottiene o imposta un elenco di scelte di completamento della chat. Può essere più di una se n è maggiore di 1. |
| [Created](../../aspose.pdf.ai/completionresponse/created/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) di quando è stata creata la completamento della chat. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ottiene o imposta il dettaglio della risposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ottiene o imposta l'errore della risposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ottiene o imposta le informazioni sull'errore. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ottiene o imposta le intestazioni della risposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ottiene o imposta il codice di stato HTTP. |
| [Id](../../aspose.pdf.ai/completionresponse/id/) { get; set; } | Ottiene o imposta un identificatore univoco per il completamento della chat. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se la risposta ha avuto successo. |
| [Model](../../aspose.pdf.ai/completionresponse/model/) { get; set; } | Ottiene o imposta il modello utilizzato per il completamento della chat. |
| [Object](../../aspose.pdf.ai/completionresponse/object/) { get; set; } | Ottiene o imposta il tipo di oggetto, che è sempre chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ottiene la frase di motivo dell'errore. |
| [SystemFingerprint](../../aspose.pdf.ai/completionresponse/systemfingerprint/) { get; set; } | Ottiene o imposta l'impronta digitale che rappresenta la configurazione del backend con cui il modello viene eseguito. Può essere usata in combinazione con il parametro di richiesta seed per capire quando sono state apportate modifiche al backend che potrebbero influire sul determinismo. |
| [Usage](../../aspose.pdf.ai/completionresponse/usage/) { get; set; } | Ottiene o imposta le statistiche di utilizzo per la richiesta di completamento. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/completionresponse/tostring/)() | Restituisce il contenuto della prima scelta come stringa. |

### Vedi anche

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


