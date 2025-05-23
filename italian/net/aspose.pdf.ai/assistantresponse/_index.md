---
title: Class AssistantResponse
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.AssistantResponse classe. Rappresenta un assistente che può chiamare il modello e utilizzare strumenti.
type: docs
weight: 140
url: /it/net/aspose.pdf.ai/assistantresponse/
---
## Classe AssistantResponse

Rappresenta un assistente che può chiamare il modello e utilizzare strumenti.

```csharp
public class AssistantResponse : BaseResponse
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [AssistantResponse](assistantresponse/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/assistantresponse/createdat/) { get; set; } | Ottiene o imposta il timestamp Unix (in secondi) per quando è stato creato l'assistente. |
| [Description](../../aspose.pdf.ai/assistantresponse/description/) { get; set; } | Ottiene o imposta la descrizione dell'assistente. La lunghezza massima è di 512 caratteri. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Ottiene o imposta il dettaglio della risposta. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Ottiene o imposta l'errore della risposta HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Ottiene o imposta le informazioni sull'errore. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Ottiene o imposta le intestazioni della risposta HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Ottiene o imposta il codice di stato HTTP. |
| [Id](../../aspose.pdf.ai/assistantresponse/id/) { get; set; } | Ottiene o imposta l'identificatore, che può essere referenziato negli endpoint API. |
| [Instructions](../../aspose.pdf.ai/assistantresponse/instructions/) { get; set; } | Ottiene o imposta le istruzioni di sistema che l'assistente utilizza. La lunghezza massima è di 256.000 caratteri. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indica se la risposta è stata positiva. |
| [Metadata](../../aspose.pdf.ai/assistantresponse/metadata/) { get; set; } | Ottiene o imposta un insieme di 16 coppie chiave-valore che possono essere collegate a un oggetto. Questo può essere utile per memorizzare informazioni aggiuntive sull'oggetto in un formato strutturato. Le chiavi possono avere una lunghezza massima di 64 caratteri e i valori possono avere una lunghezza massima di 512 caratteri. |
| [Model](../../aspose.pdf.ai/assistantresponse/model/) { get; set; } | Ottiene o imposta l'ID del modello da utilizzare. Puoi utilizzare l'API Elenco modelli per vedere tutti i tuoi modelli disponibili, o vedere la nostra panoramica del Modello per le descrizioni di essi. |
| [Name](../../aspose.pdf.ai/assistantresponse/name/) { get; set; } | Ottiene o imposta il nome dell'assistente. La lunghezza massima è di 256 caratteri. |
| [Object](../../aspose.pdf.ai/assistantresponse/object/) { get; set; } | Ottiene o imposta il tipo di oggetto, che è sempre assistente. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Ottiene la frase di motivo dell'errore. |
| [ResponseFormat](../../aspose.pdf.ai/assistantresponse/responseformat/) { get; set; } | Ottiene o imposta il formato che il modello deve restituire. Compatibile con GPT-4o, GPT-4 Turbo e tutti i modelli GPT-3.5 Turbo da gpt-3.5-turbo-1106. Impostare a { "type": "json_object" } abilita la modalità JSON, che garantisce che il messaggio generato dal modello sia un JSON valido. Importante: quando si utilizza la modalità JSON, è necessario anche istruire il modello a produrre JSON da solo tramite un messaggio di sistema o utente. Senza questo, il modello potrebbe generare un flusso infinito di spazi bianchi fino a quando la generazione non raggiunge il limite di token, risultando in una richiesta a lungo termine e apparentemente "bloccata". Nota anche che il contenuto del messaggio potrebbe essere parzialmente tagliato se finish_reason="length", il che indica che la generazione ha superato max_tokens o la conversazione ha superato la lunghezza massima del contesto. |
| [Temperature](../../aspose.pdf.ai/assistantresponse/temperature/) { get; set; } | Ottiene o imposta quale temperatura di campionamento utilizzare, tra 0 e 2. Valori più alti come 0.8 renderanno l'output più casuale, mentre valori più bassi come 0.2 lo renderanno più focalizzato e deterministico. |
| [ToolResources](../../aspose.pdf.ai/assistantresponse/toolresources/) { get; set; } | Ottiene o imposta un insieme di risorse utilizzate dagli strumenti dell'assistente. Le risorse sono specifiche per il tipo di strumento. Ad esempio, lo strumento code_interpreter richiede un elenco di ID file, mentre lo strumento file_search richiede un elenco di ID di archiviazione vettoriale. |
| [Tools](../../aspose.pdf.ai/assistantresponse/tools/) { get; set; } | Ottiene o imposta un elenco di strumenti abilitati sull'assistente. Possono esserci un massimo di 128 strumenti per assistente. Gli strumenti possono essere di tipi code_interpreter, file_search o function. |
| [TopP](../../aspose.pdf.ai/assistantresponse/topp/) { get; set; } | Ottiene o imposta un'alternativa al campionamento con temperatura, chiamata campionamento del nucleo, in cui il modello considera i risultati dei token con massa di probabilità top_p. Quindi 0.1 significa che vengono considerati solo i token che compongono il 10% superiore della massa di probabilità. In generale, raccomandiamo di modificare questo o la temperatura ma non entrambi. |

### Vedi Anche

* classe [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)