---
title: "Classe RunStepResponse"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.AI.RunStepResponse classe. Rappresenta un passaggio nell'esecuzione di un run"
type: docs
weight: 1140
url: /it/net/aspose.pdf.ai/runstepresponse/
---
## RunStepResponse class

Rappresenta un passaggio nell'esecuzione di un run.

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
| [AssistantId](../../aspose.pdf.ai/runstepresponse/assistantid/) { get; set; } | Ottiene o imposta l'ID dell'assistente associato al run step. |
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il run step è stato annullato. |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il run step è stato completato. |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il run step è stato creato. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ottiene o imposta il dettaglio della risposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ottiene o imposta l'errore della risposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ottiene o imposta le informazioni sull'errore. |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il run step è scaduto. Un run step è considerato scaduto se il run padre è scaduto. |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il run step è fallito. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ottiene o imposta le intestazioni della risposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ottiene o imposta il codice di stato HTTP. |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | Ottiene o imposta l'identificatore del run step, che può essere referenziato negli endpoint API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se la risposta ha avuto successo. |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | Ottiene o imposta l'ultimo errore associato a questo run step. Sarà null se non ci sono errori. |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | Ottiene o imposta un insieme di 16 coppie chiave-valore che possono essere associate a un oggetto. Questo può essere utile per memorizzare informazioni aggiuntive sull'oggetto in un formato strutturato. Le chiavi possono avere una lunghezza massima di 64 caratteri e i valori possono avere una lunghezza massima di 512 caratteri. |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | Ottiene o imposta il tipo di oggetto, che è sempre thread.run.step. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ottiene la frase di motivo dell'errore. |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | Ottiene o imposta l'ID dell'esecuzione a cui appartiene questo passaggio di esecuzione. |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | Ottiene o imposta il tipo di passaggio di esecuzione, che può essere sia message_creation sia tool_calls. |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | Ottiene o imposta lo stato del passaggio di esecuzione, che può essere in_progress, cancelled, failed, completed o expired. |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | Ottiene o imposta i dettagli del passaggio di esecuzione. |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | Ottiene o imposta l'ID del thread che è stato eseguito. |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | Ottiene o imposta le statistiche di utilizzo relative al passaggio di esecuzione. Questo valore sarà null mentre lo stato del passaggio di esecuzione è in_progress. |

### Vedi anche

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


