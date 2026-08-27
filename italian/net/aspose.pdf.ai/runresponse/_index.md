---
title: "Classe RunResponse"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.AI.RunResponse. Rappresenta un'esecuzione su un thread."
type: docs
weight: 1100
url: /it/net/aspose.pdf.ai/runresponse/
---
## RunResponse class

Rappresenta un'esecuzione su un thread.

```csharp
public class RunResponse : BaseResponse, IStatus
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [RunResponse](runresponse/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runresponse/assistantid/) { get; set; } | Ottiene o imposta l'ID dell'assistente utilizzato per l'esecuzione di questo run. |
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il run è stato annullato. |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il run è stato completato. |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il run è stato creato. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ottiene o imposta il dettaglio della risposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ottiene o imposta l'errore della risposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ottiene o imposta le informazioni sull'errore. |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il run scadrà. |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il run è fallito. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ottiene o imposta le intestazioni della risposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ottiene o imposta il codice di stato HTTP. |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | Ottiene o imposta l'identificatore, che può essere referenziato negli endpoint API. |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | Ottiene o imposta i dettagli sul motivo per cui il run è incompleto. Sarà null se il run non è incompleto. |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | Ottiene o imposta le istruzioni che l'assistente ha usato per questo run. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se la risposta ha avuto successo. |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | Ottiene o imposta l'ultimo errore associato a questo run. Sarà null se non ci sono errori. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | Ottiene o imposta il numero massimo di token di completamento specificati come utilizzati durante il run. |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | Ottiene o imposta il numero massimo di token di prompt specificati come utilizzati durante il run. |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | Ottiene o imposta un insieme di 16 coppie chiave-valore che possono essere associate a un oggetto. Questo può essere utile per memorizzare informazioni aggiuntive sull'oggetto in un formato strutturato. Le chiavi possono avere una lunghezza massima di 64 caratteri e i valori possono avere una lunghezza massima di 512 caratteri. |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | Ottiene o imposta il modello che l'assistente ha usato per questo run. |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | Ottiene o imposta il tipo di oggetto, che è sempre thread.run. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ottiene la frase di motivo dell'errore. |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | Ottiene o imposta i dettagli sull'azione richiesta per continuare il run. Sarà null se non è richiesta alcuna azione. |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | Ottiene o imposta il formato che il modello deve produrre. Compatibile con GPT-4o, GPT-4 Turbo e tutti i modelli GPT-3.5 Turbo a partire da gpt-3.5-turbo-1106. Impostare a { \"type\": \"json_object\" } abilita la modalità JSON, che garantisce che il messaggio generato dal modello sia JSON valido. Importante: quando si utilizza la modalità JSON, è necessario anche istruire il modello a produrre JSON tramite un messaggio di sistema o utente. Senza ciò, il modello potrebbe generare un flusso infinito di spazi bianchi finché la generazione non raggiunge il limite di token, risultando in una richiesta a lunga durata e apparentemente \"bloccata\". Nota inoltre che il contenuto del messaggio potrebbe essere parzialmente troncato se finish_reason=\"length\", il che indica che la generazione ha superato max_tokens o che la conversazione ha superato la lunghezza massima del contesto. |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando il run è stato avviato. |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | Ottiene o imposta lo stato del run, che può essere queued, in_progress, requires_action, cancelling, cancelled, failed, completed, incomplete o expired. |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | Ottiene o imposta la temperatura di campionamento usata per questo run. Se non impostata, il valore predefinito è 1. |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | Ottiene o imposta l'ID del thread su cui è stato eseguito come parte di questo run. |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | Ottiene o imposta quale (se presente) strumento è chiamato dal modello. none significa che il modello non chiamerà alcuno strumento e genererà invece un messaggio. auto è il valore predefinito e indica che il modello può scegliere tra generare un messaggio o chiamare uno o più strumenti. required significa che il modello deve chiamare uno o più strumenti prima di rispondere all'utente. Specificare uno strumento particolare come {\"type\": \"file_search\"} o {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} costringe il modello a chiamare quello strumento. |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | Ottiene o imposta l'elenco degli strumenti che l'assistente ha usato per questo run. |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | Ottiene o imposta il valore di nucleus sampling usato per questo run. Se non impostato, il valore predefinito è 1. |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | Ottiene o imposta la strategia di troncamento che controlla come un thread verrà troncato prima dell'esecuzione. Utilizzala per controllare la finestra di contesto iniziale dell'esecuzione. |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | Ottiene o imposta le statistiche di utilizzo relative all'esecuzione. Questo valore sarà nullo se l'esecuzione non è in uno stato terminale (ad es. in_progress, queued, ecc.). |

### Vedi anche

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


