---
title: Class RunStepResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.RunStepResponse. Rappresenta un passo nell'esecuzione di un run
type: docs
weight: 1060
url: /it/net/aspose.pdf.ai/runstepresponse/
---
## Classe RunStepResponse

Rappresenta un passo nell'esecuzione di un run.

```csharp
public class RunStepResponse : BaseResponse
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [RunStepResponse](runstepresponse/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runstepresponse/assistantid/) { get; set; } | Ottiene o imposta l'ID dell'assistente associato al passo del run. |
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il passo del run è stato annullato. |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il passo del run è stato completato. |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il passo del run è stato creato. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ottiene o imposta i dettagli della risposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ottiene o imposta l'errore della risposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ottiene o imposta le informazioni sull'errore. |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il passo del run è scaduto. Un passo è considerato scaduto se il run padre è scaduto. |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il passo del run è fallito. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ottiene o imposta le intestazioni della risposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ottiene o imposta il codice di stato HTTP. |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | Ottiene o imposta l'identificatore del passo del run, che può essere referenziato negli endpoint API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se la risposta è stata positiva. |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | Ottiene o imposta l'ultimo errore associato a questo passo del run. Sarà nullo se non ci sono errori. |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | Ottiene o imposta un insieme di 16 coppie chiave-valore che possono essere attaccate a un oggetto. Questo può essere utile per memorizzare informazioni aggiuntive sull'oggetto in un formato strutturato. Le chiavi possono avere una lunghezza massima di 64 caratteri e i valori possono avere una lunghezza massima di 512 caratteri. |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | Ottiene o imposta il tipo di oggetto, che è sempre thread.run.step. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ottiene la frase di motivo dell'errore. |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | Ottiene o imposta l'ID del run di cui questo passo del run fa parte. |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | Ottiene o imposta il tipo di passo del run, che può essere message_creation o tool_calls. |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | Ottiene o imposta lo stato del passo del run, che può essere in_progress, cancelled, failed, completed o expired. |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | Ottiene o imposta i dettagli del passo del run. |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | Ottiene o imposta l'ID del thread che è stato eseguito. |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | Ottiene o imposta le statistiche di utilizzo relative al passo del run. Questo valore sarà nullo mentre lo stato del passo del run è in_progress. |

### Vedi Anche

* classe [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)