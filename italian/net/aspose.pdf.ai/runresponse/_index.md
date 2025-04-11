---
title: Class RunResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.RunResponse. Rappresenta un'esecuzione su un thread
type: docs
weight: 1020
url: /it/net/aspose.pdf.ai/runresponse/
---
## Classe RunResponse

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
| [AssistantId](../../aspose.pdf.ai/runresponse/assistantid/) { get; set; } | Ottiene o imposta l'ID dell'assistente utilizzato per l'esecuzione di questa esecuzione. |
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando l'esecuzione è stata annullata. |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando l'esecuzione è stata completata. |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando l'esecuzione è stata creata. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ottiene o imposta i dettagli della risposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ottiene o imposta l'errore della risposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ottiene o imposta le informazioni sull'errore. |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando l'esecuzione scadrà. |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando l'esecuzione è fallita. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ottiene o imposta le intestazioni della risposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ottiene o imposta il codice di stato HTTP. |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | Ottiene o imposta l'identificatore, che può essere referenziato negli endpoint API. |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | Ottiene o imposta i dettagli sul motivo per cui l'esecuzione è incompleta. Sarà nullo se l'esecuzione non è incompleta. |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | Ottiene o imposta le istruzioni che l'assistente ha utilizzato per questa esecuzione. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se la risposta è stata positiva. |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | Ottiene o imposta l'ultimo errore associato a questa esecuzione. Sarà nullo se non ci sono errori. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | Ottiene o imposta il numero massimo di token di completamento specificato per essere stati utilizzati durante l'esecuzione. |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | Ottiene o imposta il numero massimo di token di prompt specificato per essere stati utilizzati durante l'esecuzione. |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | Ottiene o imposta un insieme di 16 coppie chiave-valore che possono essere collegate a un oggetto. Questo può essere utile per memorizzare informazioni aggiuntive sull'oggetto in un formato strutturato. Le chiavi possono avere una lunghezza massima di 64 caratteri e i valori possono avere una lunghezza massima di 512 caratteri. |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | Ottiene o imposta il modello che l'assistente ha utilizzato per questa esecuzione. |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | Ottiene o imposta il tipo di oggetto, che è sempre thread.run. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ottiene la frase di motivo dell'errore. |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | Ottiene o imposta i dettagli sull'azione richiesta per continuare l'esecuzione. Sarà nullo se non è richiesta alcuna azione. |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | Ottiene o imposta il formato che il modello deve restituire. Compatibile con GPT-4o, GPT-4 Turbo e tutti i modelli GPT-3.5 Turbo da gpt-3.5-turbo-1106. Impostare a { "type": "json_object" } abilita la modalità JSON, che garantisce che il messaggio generato dal modello sia un JSON valido. Importante: quando si utilizza la modalità JSON, è necessario anche istruire il modello a produrre JSON da solo tramite un messaggio di sistema o utente. Senza questo, il modello potrebbe generare un flusso infinito di spazi bianchi fino a quando la generazione non raggiunge il limite di token, risultando in una richiesta a lungo termine e apparentemente "bloccata". Si noti inoltre che il contenuto del messaggio potrebbe essere parzialmente tagliato se finish_reason="length", il che indica che la generazione ha superato max_tokens o la conversazione ha superato la lunghezza massima del contesto. |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando l'esecuzione è stata avviata. |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | Ottiene o imposta lo stato dell'esecuzione, che può essere in coda, in corso, richiede azione, annullamento, annullato, fallito, completato, incompleto o scaduto. |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | Ottiene o imposta la temperatura di campionamento utilizzata per questa esecuzione. Se non impostata, predefinita a 1. |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | Ottiene o imposta l'ID del thread che è stato eseguito come parte di questa esecuzione. |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | Ottiene o imposta quale (se presente) strumento è chiamato dal modello. none significa che il modello non chiamerà alcuno strumento e invece genera un messaggio. auto è il valore predefinito e significa che il modello può scegliere tra generare un messaggio o chiamare uno o più strumenti. required significa che il modello deve chiamare uno o più strumenti prima di rispondere all'utente. Specificare uno strumento particolare come {"type": "file_search"} o {"type": "function", "function": {"name": "my_function"}} costringe il modello a chiamare quello strumento. |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | Ottiene o imposta l'elenco degli strumenti che l'assistente ha utilizzato per questa esecuzione. |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | Ottiene o imposta il valore di campionamento del nucleo utilizzato per questa esecuzione. Se non impostato, predefinito a 1. |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | Ottiene o imposta la strategia di troncamento che controlla come un thread sarà troncato prima dell'esecuzione. Utilizzare questo per controllare la finestra di contesto iniziale dell'esecuzione. |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | Ottiene o imposta le statistiche di utilizzo relative all'esecuzione. Questo valore sarà nullo se l'esecuzione non è in uno stato terminale (cioè in corso, in coda, ecc.). |

### Vedi anche

* classe [BaseResponse](../baseresponse/)
* interfaccia [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)