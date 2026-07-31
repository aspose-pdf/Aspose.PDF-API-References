---
title: "Classe ThreadMessageResponse"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.AI.ThreadMessageResponse. Rappresenta un messaggio all'interno di un thread."
type: docs
weight: 1250
url: /it/net/aspose.pdf.ai/threadmessageresponse/
---
## ThreadMessageResponse class

Rappresenta un messaggio all'interno di un thread.

```csharp
public class ThreadMessageResponse : BaseResponse, IStatus
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ThreadMessageResponse](threadmessageresponse/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/threadmessageresponse/assistantid/) { get; set; } | Ottiene o imposta, se applicabile, l'ID dell'assistente che ha scritto questo messaggio. |
| [Attachments](../../aspose.pdf.ai/threadmessageresponse/attachments/) { get; set; } | Ottiene o imposta un elenco di file allegati al messaggio. |
| [CompletedAt](../../aspose.pdf.ai/threadmessageresponse/completedat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il messaggio è stato completato. |
| [Content](../../aspose.pdf.ai/threadmessageresponse/content/) { get; set; } | Ottiene o imposta il contenuto del messaggio in un array di testo e/o immagini. |
| [CreatedAt](../../aspose.pdf.ai/threadmessageresponse/createdat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il messaggio è stato creato. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ottiene o imposta il dettaglio della risposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ottiene o imposta l'errore della risposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ottiene o imposta le informazioni sull'errore. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ottiene o imposta le intestazioni della risposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ottiene o imposta il codice di stato HTTP. |
| [Id](../../aspose.pdf.ai/threadmessageresponse/id/) { get; set; } | Ottiene o imposta l'identificatore, che può essere referenziato negli endpoint API. |
| [IncompleteAt](../../aspose.pdf.ai/threadmessageresponse/incompleteat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il messaggio è stato contrassegnato come incompleto. |
| [IncompleteDetails](../../aspose.pdf.ai/threadmessageresponse/incompletedetails/) { get; set; } | Ottiene o imposta un messaggio incompleto, dettagli sul motivo per cui il messaggio è incompleto. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se la risposta ha avuto successo. |
| [Metadata](../../aspose.pdf.ai/threadmessageresponse/metadata/) { get; set; } | Ottiene o imposta un insieme di 16 coppie chiave-valore che possono essere associate a un oggetto. Questo può essere utile per memorizzare informazioni aggiuntive sull'oggetto in un formato strutturato. Le chiavi possono avere una lunghezza massima di 64 caratteri e i valori possono avere una lunghezza massima di 512 caratteri. |
| [Object](../../aspose.pdf.ai/threadmessageresponse/object/) { get; set; } | Ottiene o imposta il tipo di oggetto, che è sempre "thread.message". |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ottiene la frase di motivo dell'errore. |
| [Role](../../aspose.pdf.ai/threadmessageresponse/role/) { get; set; } | Ottiene o imposta l'entità che ha prodotto il messaggio. Uno tra "user" o "assistant". |
| [RunId](../../aspose.pdf.ai/threadmessageresponse/runid/) { get; set; } | Ottiene o imposta l'ID dell'esecuzione associata alla creazione di questo messaggio. Il valore è null quando i messaggi sono creati manualmente. |
| [Status](../../aspose.pdf.ai/threadmessageresponse/status/) { get; set; } | Ottiene o imposta lo stato del messaggio. Uno tra queued, in_progress, requires_action o completed. |
| [ThreadId](../../aspose.pdf.ai/threadmessageresponse/threadid/) { get; set; } | Ottiene o imposta l'ID del thread a cui appartiene questo messaggio. |

### Vedi anche

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


