---
title: "Classe CompletionCreateRequest"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.AI.CompletionCreateRequest. Rappresenta una richiesta per il punto finale Create Chat Completion"
type: docs
weight: 230
url: /it/net/aspose.pdf.ai/completioncreaterequest/
---
## CompletionCreateRequest class

Rappresenta una richiesta per il endpoint Create Chat Completion.

```csharp
public class CompletionCreateRequest
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [CompletionCreateRequest](completioncreaterequest/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FrequencyPenalty](../../aspose.pdf.ai/completioncreaterequest/frequencypenalty/) { get; set; } | Ottiene o imposta un numero compreso tra -2.0 e 2.0. I valori positivi penalizzano i nuovi token in base alla loro frequenza esistente nel testo finora, diminuendo la probabilità che il modello ripeta la stessa riga alla lettera. |
| [LogitBias](../../aspose.pdf.ai/completioncreaterequest/logitbias/) { get; set; } | Ottiene o imposta la probabilità che token specifici compaiano nella completazione. Accetta un oggetto JSON che mappa i token (specificati dal loro ID token nel tokenizer) a un valore di bias associato da -100 a 100. |
| [Logprobs](../../aspose.pdf.ai/completioncreaterequest/logprobs/) { get; set; } | Ottiene o imposta se restituire le probabilità logaritmiche dei token di output o meno. Se vero, restituisce le probabilità logaritmiche di ciascun token di output restituito nel contenuto del messaggio. |
| [MaxCompletionTokens](../../aspose.pdf.ai/completioncreaterequest/maxcompletiontokens/) { get; set; } | Ottiene o imposta il numero massimo di token da generare nella completamento. |
| [Messages](../../aspose.pdf.ai/completioncreaterequest/messages/) { get; set; } | Ottiene o imposta un elenco di messaggi che compongono la conversazione fino a ora. |
| [Model](../../aspose.pdf.ai/completioncreaterequest/model/) { get; set; } | Ottiene o imposta l'ID del modello da utilizzare. |
| [NumberOfChoices](../../aspose.pdf.ai/completioncreaterequest/numberofchoices/) { get; set; } | Ottiene o imposta quante scelte di completamento della chat generare per ogni messaggio di input. Nota che verrà addebitato in base al numero di token generati su tutte le scelte. Mantieni n a 1 per ridurre i costi. |
| [PresencePenalty](../../aspose.pdf.ai/completioncreaterequest/presencepenalty/) { get; set; } | Ottiene o imposta un numero compreso tra -2,0 e 2,0. I valori positivi penalizzano i nuovi token in base al fatto che compaiano nel testo finora, aumentando la probabilità che il modello parli di nuovi argomenti. |
| [ResponseFormat](../../aspose.pdf.ai/completioncreaterequest/responseformat/) { get; set; } | Ottiene o imposta un oggetto che specifica il formato che il modello deve restituire. Compatibile con GPT-4 Turbo e tutti i modelli GPT-3.5 Turbo più recenti di gpt-3.5-turbo-1106. Impostare a { "type": "json_object" } abilita la modalità JSON, che garantisce che il messaggio generato dal modello sia JSON valido. |
| [Seed](../../aspose.pdf.ai/completioncreaterequest/seed/) { get; set; } | Ottiene o imposta il valore Seed. Questa funzionalità è in beta. Se specificato, il nostro sistema cercherà di campionare in modo deterministico, in modo che richieste ripetute con lo stesso seed e gli stessi parametri restituiscano lo stesso risultato. Il determinismo non è garantito e dovresti fare riferimento al parametro di risposta system_fingerprint per monitorare le modifiche nel backend. |
| [Stop](../../aspose.pdf.ai/completioncreaterequest/stop/) { get; set; } | Ottiene o imposta fino a 4 sequenze in cui l'API interromperà la generazione di ulteriori token. |
| [Stream](../../aspose.pdf.ai/completioncreaterequest/stream/) { get; set; } | Ottiene o imposta se utilizzare lo streaming. Se impostato, i delta dei messaggi parziali verranno inviati, come in ChatGPT. I token saranno inviati come eventi server-sent solo dati non appena disponibili, con lo stream terminato da un messaggio data: [DONE]. |
| [Temperature](../../aspose.pdf.ai/completioncreaterequest/temperature/) { get; set; } | Ottiene o imposta la temperatura di campionamento da utilizzare, tra 0 e 2. Valori più alti come 0,8 renderanno l'output più casuale, mentre valori più bassi come 0,2 lo renderanno più concentrato e deterministico. |
| [ToolChoice](../../aspose.pdf.ai/completioncreaterequest/toolchoice/) { get; set; } | Ottiene o imposta un oggetto che controlla quale (se presente) strumento è chiamato dal modello. none significa che il modello non chiamerà alcuno strumento e genererà invece un messaggio. auto significa che il modello può scegliere tra generare un messaggio o chiamare uno o più strumenti. required significa che il modello deve chiamare uno o più strumenti. Specificare uno strumento particolare tramite {"type": "function", "function": {"name": "my_function"}} forza il modello a chiamare quello strumento. none è il valore predefinito quando non sono presenti strumenti. auto è il valore predefinito se sono presenti strumenti. |
| [Tools](../../aspose.pdf.ai/completioncreaterequest/tools/) { get; set; } | Ottiene o imposta un elenco di strumenti che il modello può chiamare. Attualmente, solo le funzioni sono supportate come strumento. Usa questo per fornire un elenco di funzioni per le quali il modello può generare input JSON. È supportato un massimo di 128 funzioni. |
| [TopP](../../aspose.pdf.ai/completioncreaterequest/topp/) { get; set; } | Ottiene o imposta un'alternativa al campionamento con temperatura, chiamata campionamento nucleare, in cui il modello considera i risultati dei token con massa di probabilità top_p. Quindi 0,1 significa che vengono considerati solo i token che compongono il 10% superiore della massa di probabilità. |
| [User](../../aspose.pdf.ai/completioncreaterequest/user/) { get; set; } | Ottiene o imposta un identificatore univoco che rappresenta il tuo utente finale, il quale può aiutare OpenAI a monitorare e rilevare abusi. |

### Vedi anche

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


