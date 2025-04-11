---
title: Class RunCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.RunCreateRequest class. Represents a request to create a run
type: docs
weight: 980
url: /it/net/aspose.pdf.ai/runcreaterequest/
---
## Classe RunCreateRequest

Rappresenta una richiesta per creare un run.

```csharp
public class RunCreateRequest
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [RunCreateRequest](runcreaterequest/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AdditionalInstructions](../../aspose.pdf.ai/runcreaterequest/additionalinstructions/) { get; set; } | Ottiene o imposta le istruzioni aggiuntive. Aggiunge istruzioni aggiuntive alla fine delle istruzioni per il run. Questo è utile per modificare il comportamento su base per run senza sovrascrivere altre istruzioni. |
| [AdditionalMessages](../../aspose.pdf.ai/runcreaterequest/additionalmessages/) { get; set; } | Ottiene o imposta i messaggi aggiuntivi al thread prima di creare il run. |
| [AssistantId](../../aspose.pdf.ai/runcreaterequest/assistantid/) { get; set; } | Ottiene o imposta l'ID dell'assistente da utilizzare per eseguire questo run. |
| [Instructions](../../aspose.pdf.ai/runcreaterequest/instructions/) { get; set; } | Ottiene o imposta le istruzioni che sovrascrivono le istruzioni dell'assistente. Questo è utile per modificare il comportamento su base per run. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runcreaterequest/maxcompletiontokens/) { get; set; } | Ottiene o imposta il numero massimo di token di completamento che possono essere utilizzati nel corso del run. Il run farà del suo meglio per utilizzare solo il numero di token di completamento specificato, attraverso più turni del run. Se il run supera il numero di token di completamento specificato, il run terminerà con stato incompleto. Vedi incomplete_details per ulteriori informazioni. |
| [MaxPromptTokens](../../aspose.pdf.ai/runcreaterequest/maxprompttokens/) { get; set; } | Ottiene o imposta il numero massimo di token di prompt che possono essere utilizzati nel corso del run. Il run farà del suo meglio per utilizzare solo il numero di token di prompt specificato, attraverso più turni del run. Se il run supera il numero di token di prompt specificato, il run terminerà con stato incompleto. Vedi incomplete_details per ulteriori informazioni. |
| [Metadata](../../aspose.pdf.ai/runcreaterequest/metadata/) { get; set; } | Ottiene o imposta un insieme di 16 coppie chiave-valore che possono essere collegate a un oggetto. Questo può essere utile per memorizzare informazioni aggiuntive sull'oggetto in un formato strutturato. Le chiavi possono avere una lunghezza massima di 64 caratteri e i valori possono avere una lunghezza massima di 512 caratteri. |
| [Model](../../aspose.pdf.ai/runcreaterequest/model/) { get; set; } | Ottiene o imposta l'ID del modello da utilizzare per eseguire questo run. Se viene fornito un valore qui, sovrascriverà il modello associato all'assistente. In caso contrario, verrà utilizzato il modello associato all'assistente. |
| [ResponseFormat](../../aspose.pdf.ai/runcreaterequest/responseformat/) { get; set; } | Ottiene o imposta il formato di risposta. Specifica il formato che il modello deve restituire. Compatibile con GPT-4o, GPT-4 Turbo e tutti i modelli GPT-3.5 Turbo da gpt-3.5-turbo-1106. Impostare a { "type": "json_object" } abilita la modalità JSON, che garantisce che il messaggio generato dal modello sia un JSON valido. Importante: quando si utilizza la modalità JSON, è necessario anche istruire il modello a produrre JSON da solo tramite un messaggio di sistema o utente. Senza questo, il modello potrebbe generare un flusso infinito di spazi bianchi fino a quando la generazione non raggiunge il limite di token, risultando in una richiesta a lungo termine e apparentemente "bloccata". Nota anche che il contenuto del messaggio potrebbe essere parzialmente tagliato se finish_reason="length", il che indica che la generazione ha superato max_tokens o la conversazione ha superato la lunghezza massima del contesto. |
| [Stream](../../aspose.pdf.ai/runcreaterequest/stream/) { get; set; } | Ottiene o imposta se utilizzare lo streaming. Se vero, restituisce un flusso di eventi che accadono durante il Run come eventi inviati dal server, terminando quando il Run entra in uno stato terminale con un messaggio data: [DONE]. |
| [Temperature](../../aspose.pdf.ai/runcreaterequest/temperature/) { get; set; } | Ottiene o imposta quale temperatura di campionamento utilizzare, tra 0 e 2. Valori più alti come 0.8 renderanno l'output più casuale, mentre valori più bassi come 0.2 lo renderanno più focalizzato e deterministico. |
| [ToolChoice](../../aspose.pdf.ai/runcreaterequest/toolchoice/) { get; set; } | Ottiene o imposta quale (se presente) strumento è chiamato dal modello. none significa che il modello non chiamerà alcun strumento e invece genera un messaggio. auto è il valore predefinito e significa che il modello può scegliere tra generare un messaggio o chiamare uno o più strumenti. required significa che il modello deve chiamare uno o più strumenti prima di rispondere all'utente. Specificare uno strumento particolare come {"type": "file_search"} o {"type": "function", "function": {"name": "my_function"}} costringe il modello a chiamare quello strumento. |
| [Tools](../../aspose.pdf.ai/runcreaterequest/tools/) { get; set; } | Ottiene o imposta gli strumenti che sovrascrivono gli strumenti che l'assistente può utilizzare per questo run. Questo è utile per modificare il comportamento su base per run. |
| [TopP](../../aspose.pdf.ai/runcreaterequest/topp/) { get; set; } | Ottiene o imposta un'alternativa al campionamento con temperatura, chiamata campionamento del nucleo, dove il modello considera i risultati dei token con massa di probabilità top_p. Quindi 0.1 significa che vengono considerati solo i token che compongono il 10% superiore della massa di probabilità. In generale, raccomandiamo di modificare questo o la temperatura ma non entrambi. |
| [TruncationStrategy](../../aspose.pdf.ai/runcreaterequest/truncationstrategy/) { get; set; } | Ottiene o imposta la strategia di troncamento. Controlla come un thread sarà troncato prima del run. Usa questo per controllare la finestra di contesto iniziale del run. |

### Vedi anche

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)